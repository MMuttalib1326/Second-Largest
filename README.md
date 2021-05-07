# Second-Largest
Python programming

t=int(input())
while(t):
    l=[int(i) for i in input().split()]
    l=sorted(l)
    print(l[-2])
    t=t-1
