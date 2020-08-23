# fib.py
the code can be used to print fibonacci series using python language
n=int(input("Enter the value of n"))
a=0
b=1
sum=0
count=1
print("fibonacci series: ")
while (count<=n):
    print(sum)
    count+=1
    a=b
    b=sum
    sum=a+b
    
    
