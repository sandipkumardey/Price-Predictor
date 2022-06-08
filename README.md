x=y=z=0
x= float(input("Enter first number :"))
y= float(input("Enter first number :"))
z= float(input("Enter first number :"))
max=x
if y>max:
    max=y
if z>max:
    max=z
print("Largest no is", max)

x=y=z=0
x= int(input("Enter first number :"))
y= int(input("Enter first number :"))
z= int(input("Enter first number :"))
min=mid=max=None
if x<y and x<z:
    if y<z:
        min,mid,max=x,y,z
    else:
        min,mid,max=x,y,z
elif y<x and y<z:
    if x<z:
        min,mid,max=x,y,z
    else:
        min,mid,max=x,y,z
else:
    if x<y:
        min,mid,max=x,y,z
    else:
        min,mid,max=x,y,z
print("Number in asc order:", min, mid, max)


num= int(input("Enter a no: "))
fact= 1
a=1
while a<= num:
    fact *= a
    a += 1
print("The factorial of", num, "is", fact)



n= int(input("Enter no :"))
for i in range(1,11):
    print(n,"x",i, "=", (n*i))



