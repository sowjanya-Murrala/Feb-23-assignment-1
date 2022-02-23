l=[]
n=int(input("enter number:"))
for i in range(n):
    e=int(input("enter number:"))
    l.append(e)
    max=l[0]
for i in range (l,n):
    if l[i]>max:
        max=l[i]
print("max",max)
min=l[0]
for i in range(1,n):
    if l[i]<min:
        min=l[i]
print("min",min)
