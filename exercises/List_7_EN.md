# Exercises with Threads, Multiprocessing, `concurrent.futures`, and `dask`

## 1. Creating a Simple Thread
Create a function called `print_numbers` that prints numbers from 1 to 5 with a 1-second pause between them. Run this function in a separate thread using the `threading` module;

## 2. Using Multiple Threads
Modify the previous exercise to run two threads that print numbers from 1 to 5 simultaneously. Ensure that the program waits for both threads to finish before exiting;

## 3. Synchronization with Threads
Implement a shared counter between two threads. The threads should increment the counter 1000 times each. Use a `Lock` to prevent race conditions and ensure that the final counter value is 2000;

## 4. Multiprocessing with Simple Processes
<font color = "yellow"> Warning: </font> Do this exercise on a Linux Operating System (like on Google Colab). It is not recommended to use `multiprocessing` on Windows due to the OS's process management. If run on Windows, it will take much longer to execute than a simple `for` loop. [Explanation here](https://stackoverflow.com/questions/52465237/multiprocessing-slower-than-serial-processing-in-windows-but-not-in-linux).

Create a program that starts two parallel processes using the `multiprocessing` module, where each process calculates the square of numbers from 1 to 5. Display the results at the end;

## 5. Data Sharing Between Processes
<font color = "yellow"> Warning: </font> Do this exercise on a Linux Operating System (like on Google Colab). It is not recommended to use `multiprocessing` on Windows due to the OS's process management. If run on Windows, it will take much longer to execute than a simple `for` loop. [Explanation here](https://stackoverflow.com/questions/52465237/multiprocessing-slower-than-serial-processing-in-windows-but-not-in-linux).

Using the `multiprocessing` module, create a `Queue` to share data between two processes. The first process should add numbers from 1 to 5 into the queue, while the second process removes and prints those numbers;

## 6. Process Pool
<font color = "yellow"> Warning: </font> Do this exercise on a Linux Operating System (like on Google Colab). It is not recommended to use `multiprocessing` on Windows due to the OS's process management. If run on Windows, it will take much longer to execute than a simple `for` loop. [Explanation here](https://stackoverflow.com/questions/52465237/multiprocessing-slower-than-serial-processing-in-windows-but-not-in-linux).

Implement a program that uses `multiprocessing.Pool` to calculate the squares of a list of numbers. Use 4 processes in the pool to parallelize the execution;

## 7. Using `concurrent.futures.ThreadPoolExecutor`
Create a function that calculates the factorial of a number and runs it in parallel for 5 different numbers using `concurrent.futures.ThreadPoolExecutor`. Display the final result of each execution;

## 8. Using `concurrent.futures.ProcessPoolExecutor`
Implement the calculation of the Fibonacci number for 5 different values, using `concurrent.futures.ProcessPoolExecutor` to execute the calculation in parallel processes. Print the results;

## 9. Waiting for Future Results
Modify the previous exercise to collect and display the results as they are completed, using the `as_completed()` method from the `concurrent.futures` library;

## 10. Introduction to Dask - Simple Operations
Using the `dask` library, create a random array of 1 million elements and compute the total sum of the values in parallel. Display the execution time of the code;

## 11. Deferred Computations with Dask
Implement a series of mathematical operations (addition, multiplication, subtraction) on Dask arrays and execute them "lazily" (without immediate computation). Use `compute()` to calculate the results at the end;

## 12. Using Dask DataFrame
Load a large CSV dataset using `dask.dataframe`. Perform a simple aggregation (such as mean or sum) on a numeric column and display the results;