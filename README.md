# Symmetric_difference
To print the symmetric difference of a set in ascending order.
n1=int(input())
a=set(map(int,input().split()))
n2=int(input())
b=set(map(int,input().split()))
s=(a.difference(b)).union(b.difference(a))
#print(len(s))
s=sorted(s)
for i in s:
    print(i)
