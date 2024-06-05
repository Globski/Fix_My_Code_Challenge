# Fix My Code - Challenge

## Description
In this project, you'll dive into debugging existing code bases, focusing on identifying and fixing issues without recoding everything from scratch. This hands-on experience will help you improve your problem-solving and debugging skills across various programming languages.

## Project Structure

| Task                   | Description                                                          | Source Code                  |
|------------------------|----------------------------------------------------------------------|------------------------------|
| FizzBuzz               | Fix the implementation of FizzBuzz in Python.                        | [0-fizzbuzz.py](0-fizzbuzz.py)  |
| Print square           | Fix the implementation of printing a square in JavaScript.           | [1-print_square.js](1-print_square.js)  |
| Sort                   | Fix the implementation of sorting arguments in Ruby.                 | [2-sort.rb](2-sort.rb)  |
| User password          | Fix the implementation of a User class in Python.                    | [3-user.py](3-user.py)  |
| Double linked list     | Fix the implementation of a Double linked list in C.                 | [4-delete_dnodeint](4-delete_dnodeint)  |

## Environment

- All files will be compiled and tested on Ubuntu 20.04 LTS.

## Requirements

- All files should end with a new line.

## Background Context
Fix my code is a new type of project, where you’ll jump into an existing code base and fix it! Sometimes you will know the language, sometimes not. You should not recode everything, just fix the issues identified.

## Tasks
### 0. FizzBuzz
**#advanced**

Fix the implementation of FizzBuzz in Python.  
**Source Code:** [0-fizzbuzz.py](0-fizzbuzz.py)

```shell
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```
15 should print FizzBuzz not Fizz.

### 1. Print square
**#advanced**

Fix the implementation of printing a square in JavaScript.  
**Source Code:** [1-print_square.js](1-print_square.js)

```shell
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
$
```
./1-print_square.js 10 should print a square of size 10.

### 2. Sort
**#advanced**

Fix the implementation of sorting arguments in Ruby.  
**Source Code:** [2-sort.rb](2-sort.rb)

```shell
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$
```

### 3. User password
**#advanced**

Fix the implementation of a User class in Python.  
**Source Code:** [3-user.py](3-user.py)

```shell
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```
My tests should not print any error.

### 4. Double linked list
**#advanced**

Fix the implementation of a Double linked list in C.  
**Source Code:** [4-delete_dnodeint](4-delete_dnodeint)

```shell
$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```
It doesn’t look right…

## How to Use
- Clone the repository to your local machine.
- Navigate to the project directory `0x00-challenge`.
- Identify and fix the issues in the provided code.
- Test your fixes to ensure the code runs correctly.
