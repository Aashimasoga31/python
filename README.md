a = input("data1: ")
b = input("data2: ")
a = a.split(',')
b = b.split(',')
#create a dictinaory with the lists
d1 = sorted(dict(zip(a,b)).items())
print("dictionary with key order")
for key,value in d1:
  print(key,value)
d2 = sorted(dict(zip(b,a)).items())
print("dictionary with value order")
for key,value in d2:
  print(key,value)
