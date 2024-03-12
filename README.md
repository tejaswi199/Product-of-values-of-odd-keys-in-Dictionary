n=int(input())
d={}
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
m=1
for j in d:
  if j%2 != 0:
    m=m*d[j]
print(m)
