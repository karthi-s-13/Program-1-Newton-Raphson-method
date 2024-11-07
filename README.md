# Program 1: Newton Raphson method

## Question:

Find a positive real root of $$x^3$$ − 𝒙 − 𝟐 = 𝟎 using Newton-Raphson method.

## Aim:

To find a positive real root of $$x^3$$ − 𝒙 − 𝟐 = 𝟎 by using Newton-Raphson method.

## Algorithm:

Step 1: Define the function f(x) = x**3 - x - 2

Step 2: Define the function $$f_1$$ = 3*x ** 2 - 1

Step 3: Get the value of $$X_0$$

Step 4: for i = 1 to 9
        $$X_n$$ = $$X_0$$ - $$\frac{f(x_0)}{f^1(x_0)}$$
        $$X_0$$ = $$X_n$$

Step 5: Print the value of $$X_n$$

## Program:
```
def f(x):
 return x**3-x-2
def f1(x):
 return 3*x**2-1
xo=float (input ("Enter the initial approximation: "))
for i in range (1,10):
 xn=xo-f(xo)/f1(xo)
 xo=xn
print ("The approximate root using Newton-Raphson method is %.4f"%xn)
```

## Output:

Enter the initial approximation: 1
The approximate root using Newton-Raphson method is 1.5214

## Result:

