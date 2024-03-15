# python-dictionaries
#simple dictionary

d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
print(d)  

#accessing elements
d={10:100,20:200,30:300,40:400}
for i in d:
  print(i)
for i in d:
  print(d[i])


#accessing keys and values
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
for i in d:
  print(f"{i}->{d[i]}")


#addition of values in dictionary
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=0 
for i in d:
  res=res+d[i]
  print(res)

#approach 2

d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=d.values()
print(sum(res))

