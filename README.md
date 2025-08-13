# 1.check given number is even or odd using python

num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even")
else:
    print("Odd")
    
# output:
<img width="890" height="153" alt="image" src="https://github.com/user-attachments/assets/f7db7d06-31f7-4683-b28d-2e39023d330c" />


# 2.largest of three numbers

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Largest is", a)
elif b >= a and b >= c:
    print("Largest is", b)
else:
    print("Largest is", c)

# output:
<img width="922" height="182" alt="image" src="https://github.com/user-attachments/assets/bfb03d08-02c3-4b95-8086-ff8bc48ec326" />


# 3.Fibonacci series
 n = int(input("Enter number of terms: "))
a, b = 0, 1
for _ in range(n):
    print(a, end=" ")
    a, b = b, a + b

# output:
<img width="924" height="156" alt="image" src="https://github.com/user-attachments/assets/8be760cd-c715-4206-8576-1e0ebc04ed44" />


# 4.Reverse a string
s = input("Enter a string: ")
print("Reversed:", s[::-1])

# output:
<img width="922" height="182" alt="image" src="https://github.com/user-attachments/assets/83ff315b-4d35-4c3f-a80b-9f7b54847f1e" />


