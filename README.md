l=[]
n=int(input('enter n:'))
for i in range(0,n):
    e=int(input('enter number:'))
    l.append(e)
min=l[0]
for i in range (1,n):
    if l[i]<min:
        min=l[i]
print('minimum number is:',min)
max=l[0]
for j in range (1,n):
    if l[j]>max:
        max=l[j]
print('maximum number is:',max)

Output:
enter n:4
enter number:12
enter number:70
enter number:04
enter number:50
minimum number is: 4
maximum number is: 70
>
