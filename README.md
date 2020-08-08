# How-to-Talk-Matlab

April 26, 2020

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me!

I Love Math, hehehe!

Our data are exploding in size & dimensions and we have sophisticated computer
tools to handle processing. Data are stored in variables and arrays. We can use
arrays to store related data in one variable. Python has the "list" data 
structure natively but has to cater to many data types so it is general purpose. 
Hence, is not the most optimized. To the rescue are the fast NumPy arrays,
another library, that is very efficient for numerical computing. It is designed
for number crunching. On to Matlab, arrays are used throughout MATLAB. In fact,
MATLAB is an abbreviation for MATrix LABoratory. All MATLAB variables are 
arrays. This means that each variable can contain multiple elements. 

Number crunching is our core activity, so we need proficiency in array 
operations. Let's start with using indexing to extract and modify rows, columns,
and elements of MATLAB arrays. We extract columns, compare logical operations
on column or row values, modify elements using assignment, and a variety of 
effects we may think of. For example, if we want to access, we index the array.
Index tells us the position within the array. Whereas, if we want to modify an
element or elements, we use assignment.

What follows is a sample live script to exercise getting our proficiency. Any
unfamiliar function we look up using the many help options at our disposal.

n = rand(5,4)

v = [16 5 9 4 2 11 7 14];

v(3)

v([1 5 6])

v(3:7)

v2 = v([5:8 1:4]) 

v(end)

v(5:end)

v(2:end-1)

v(1:2:end)

v([2 3 4]) = [10 15 20] 

v([2 3]) = 30

A = magic(4)

A(2,4)

A(2:4,1:2)

A(3,:)

A(A > 12)

A(isnan(A)) = 0

x = rand(5,1)

x = zeros(6,3)

x = linspace(1,10,5)

x = 1:3

x = x'

who

%clear

%clc

I included some posts for reference.

https://github.com/noey2020/How-to-Talk-Linear-Algebra

https://github.com/noey2020/How-to-Make-Predictions-in-Python

https://github.com/noey2020/How-to-Talk-Hashing

https://github.com/noey2020/How-to-Talk-Algorithm-Analysis

https://github.com/noey2020/How-to-Talk-Recursion

https://github.com/noey2020/How-to-Talk-Linked-Lists

https://github.com/noey2020/How-to-Talk-Queues

https://github.com/noey2020/How-to-Talk-Stacks

https://github.com/noey2020/How-to-Talk-Lists-Stacks-and-Queues

https://github.com/noey2020/How-to-Talk-Linear-Regression

https://github.com/noey2020/How-to-Talk-Statistics-Pattern-Recognition-101

https://github.com/noey2020/How-to-Write-SPI-STM32

https://github.com/noey2020/How-to-Write-SysTick-Handler-for-STM32

https://github.com/noey2020/How-to-Write-Subroutines-in-C-Assembly-STM32

https://github.com/noey2020/How-to-Write-Multitasking-STM32

https://github.com/noey2020/How-to-Generate-Triangular-Wave-STM32-DAC

https://github.com/noey2020/How-to-Generate-Sine-Table-LUT

https://github.com/noey2020/How-to-Illustrate-Multiple-Exceptions-

https://github.com/noey2020/How-to-Blink-LED-using-Standard-Peripheral-Library

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me!

Have fun and happy coding!
