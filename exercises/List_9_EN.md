# Exercises with Numba and Cupy

## 1. Simple JIT Function
Create a function that calculates the sum of all elements in a list of integers. Use the `@jit` decorator from Numba to speed up execution, and compare the execution time with and without JIT compilation;

## 2. Matrix Multiplication with JIT
Create a function to multiply two `500x500` matrices using the `@jit` decorator. Generate two random matrices, multiply them, and measure the execution time with and without JIT;

## 3. Prime Number Calculation with JIT
Create a function that returns all prime numbers up to a user-provided number `n`. Use Numba with JIT to optimize the function and compare execution time for large values of `n`;

## 4. Matrix Multiplication with Cupy
Create two `1000x1000` matrices using Cupy and compute their product directly on the GPU;

## 5. Outer Product of Vectors with Cupy
Using Cupy, calculate the outer product of two vectors of size `10000`;