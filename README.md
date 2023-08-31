# Fibonacci-Series-using-recursion-
The code is a recursive function that prints the Fibonacci sequence. The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding numbers. The first two numbers in the sequence are 0 and 1.

The code first declares a class called fibonacci. The class has two methods: printFib() and main().

The printFib() method takes three arguments: the first two Fibonacci numbers, and the number of terms to print. The method first checks if the number of terms is 0. If it is, the method returns. Otherwise, the method does the following:

It calculates the next Fibonacci number by adding the two previous numbers.
It prints the next Fibonacci number.
It calls the printFib() method again, but with the two previous Fibonacci numbers as the first two arguments, and the number of terms reduced by 1.
The main() method first prints the first two Fibonacci numbers, 0 and 1. Then, it calls the printFib() method with the arguments 0, 1, and 7. This means that the printFib() method will print the first 7 Fibonacci numbers, starting from 0
