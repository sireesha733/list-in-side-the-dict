# list-in-side-the-dict
d={}
n=int(input())
for i in range(1,n+1):
  d[i]=[]
  for j in range(1,i+1):
    if i%j==0:
      d[i].append(j)
print(d)
