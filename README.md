a,b = 0,1
n  = int(input())
for i in range(n+1):
    print(a)
    a,b = b,a+b
    
