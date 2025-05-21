# Program 1: Newton Raphson method

<br>

## Date: 21-05-2025


## Name: KARTHIKEYAN S
## Reg No: 212224230116

<br>

## Question:

<br>

   Find a positive real root of $$x^3$$ − 𝒙 − 𝟐 = 𝟎 using Newton-Raphson method.

<br>

## Aim:

<br>

   To find a positive real root of $$x^3$$ − 𝒙 − 𝟐 = 𝟎 by using Newton-Raphson method.

<br>

## Algorithm:

<br>

   Step 1: Define the function $$f(x) = x**3 - x - 2$$

<br>

   Step 2: Define the function $$f_1 = 3* x **2 - 1$$

<br>

   Step 3: Get the value of $$X_0\$$

<br>

   Step 4: for i = 1 to 9

$$
X_n = X_0 - \frac{f(X_0)}{f^1(X_0)}
$$

<br>

$$
X_0 = X_n
$$

   Step 5: Print the value of $$X_n$$

<br>

## Program:

<br>

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

<br>

## Output:

<br>

Enter the initial approximation: 1

<br>

The approximate root using Newton-Raphson method is 1.5214

<br>

## Result:

<br>

The real root of the given non linear equation is obtained

