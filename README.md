```
fib = int(input('Enter the no. of terms in fib series:'))
a=0
b=1
count=0

for i in range(0,101):
    if fib <= 0:
        print("Enter a positive no.")
    elif fib == 1:
        print("Fib sequence upto",fib,":")
        print(0)
    else:
        while count < fib:
            print(a)
            n = a + b
            a = b
            b = n
            count += 1
```



```
#swapping two numbers
a = 10
b = 6

a = a + b
b = a - b
a = a - b

print(a)
print(b)
```


```
marks = int(input("Enter the marks:"))

if marks<35:
    print('Sorry! You have failed..')
elif marks>=35 and marks <= 75:
    print('Awesome! You have pass in First Class..')
elif marks > 75:
    print('Excellent! You have achieved distinction..')
```
