# Project 3: Producer-Consumer Problem with Circular Buffer

## Description
This project implements the **Producer-Consumer problem** using a circular buffer and named semaphores. The producer reads characters from a file (`mytest.dat`) and writes them to a shared buffer, while the consumer processes and prints these characters. The program stops processing when the special end marker (`*`) is encountered.

---

## How to Compile and Run
1. To compile the program, run the following command in the terminal:
```bash
  gcc pro3.c -o pro3 -lpthread -lrt
2. How to Run to execute the program, run:
```bash
./pro3

