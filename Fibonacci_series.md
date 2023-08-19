# Assignment-1
Question 1: Let's play with fibonacci
#Python Code:
i=a=0
b=1
n=int(input("enter the number:"))
while i<n:
    c=a+b
    a=b
    b=c
    print(c,end=" ")
    i+=1
