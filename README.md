# Project 3: Producer-Consumer Problem with Circular Buffer

## Description
This project implements the **Producer-Consumer problem** using a circular buffer and named semaphores. The producer reads characters from a file (`mytest.dat`) and writes them to a shared buffer, while the consumer processes and prints these characters. The program stops processing when the special end marker (`*`) is encountered.

---

## How to Compile
To compile the program, run the following command in the terminal:
gcc pro3.c -o pro3 -lpthread -lrt

## How to Run
To execute the program, run:
./pro3

