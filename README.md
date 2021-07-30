#pattern-1
#0 0 0 0 0 0 
#1 1 1 1 1 1 
#2 2 2 2 2 2 
#3 3 3 3 3 3 
#4 4 4 4 4 4 
#5 5 5 5 5 5
num=int(input())
for i in range(num):
    for j in range(num):
        print(i,end=" ")
    print() 



#pattern-2
#1 
#2 2 
#3 3 3 
#4 4 4 4 
#5 5 5 5 5 
#6 6 6 6 6 6 

num=int(input())
for i in range(num+1):
    for j in range(i):
        print(i,end=" ")
    print()
    
#pattern-3

#0 
#0 1 
#0 1 2 
#0 1 2 3 
#0 1 2 3 4 
#0 1 2 3 4 5 
num=int(input())
for i in range(num+1):
    for j in range(i):
        print(j,end=" ")
    print()
    
#pattern-4
num=int(input())
for i in range(num+1):
    for j in range(i):
        print(j,end=" ")
    print()
    
#pattern-5
#5 5 5 5 5 
#4 4 4 4 
#3 3 3 
#2 2 
#1     
n=int(input())
for i in range(n,0,-1):
    for j in range(1,i+1):
        print(i,end=" ")
    print()
    
#pattern-6
#1 2 3 4 5 
#1 2 3 4 
#1 2 3 
#1 2 
#1

n=int(input())
for i in range(n,0,-1):
    for j in range(1,i+1):
        print(j,end=" ")
    print()

#pattern-7
#5 4 3 2 1 
#4 3 2 1 
#3 2 1 
#2 1 
#1

n=int(input())
for i in range(n,0,-1):
    a=i
    for j in range(i):
        print(a,end=" ")
        a-=1
        
    print()
