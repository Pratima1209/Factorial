# Factorial
#Python Program for factorial of a number

n=int(input("Enter the number:"))
result=1
for i in range(n,0,-1):
    result=result*i
print(result)

