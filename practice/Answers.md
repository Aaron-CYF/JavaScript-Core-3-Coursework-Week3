# Code reading

## Question 1

Line 4 and 7 have different outputs because of the scope of the `f1()` function makes `x` a different variable.

## Question 2

The first line will be 10; `x` is inherited into the scope of `f1()`.
The second will be undefined; the console log is getting output from `f1()` which has no return.
The third will be "error: y is not defined"; y does not exist outside the scope of `f1()`.

## Question 3

The first output is 9; `f1()` doesn't modify `x` which only it's value is passed.
The second is { x: 10 }; `y` is an object so it's reference is passed and the original variable data is modified.
