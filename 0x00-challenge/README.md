# Fix My Code Challenge

## Description
The Fix My Code Challenge is a series of coding challenges designed to improve your debugging and problem-solving skills. In this challenge, you'll be presented with snippets of broken code in a variety of programming languages. Your task is to identify and correct the problems so that the code works as intended. Rather than coding from scratch, you'll focus on troubleshooting and fixing the existing code. This hands-on experience will help you hone your ability to debug and improve code efficiently, preparing you for real-world programming scenarios.

## Project Structure

| Task                   | Description                                                          | Source Code                  |
|------------------------|----------------------------------------------------------------------|------------------------------|
| FizzBuzz               | Fix the implementation of FizzBuzz in Python.                        | [0-fizzbuzz.py](0-fizzbuzz.py)  |
| Print square           | Fix the implementation of printing a square in JavaScript.           | [1-print_square.js](1-print_square.js)  |
| Sort                   | Fix the implementation of sorting arguments in Ruby.                 | [2-sort.rb](2-sort.rb)  |
| User password          | Fix the implementation of a User class in Python.                    | [3-user.py](3-user.py)  |
| Double linked list     | Fix the implementation of a Double linked list in C.                 | [4-delete_dnodeint](4-delete_dnodeint)  |


## Background Context
Fix my code is a new type of project, where you’ll jump into an existing code base and fix it! Sometimes you will know the language, sometimes not. You should not recode everything, just fix the issues identified.

## Environment

- **Compilation:** Ubuntu 20.04 LTS

## Requirements

- **File Conventions:** All files must end with a new line

## Learning Objectives

- Gain experience in debugging and fixing code in different programming languages.
- Improve problem-solving skills by identifying and resolving issues in existing code.
- Understand the intricacies of language-specific syntax and functionality.


## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Fix_My_Code_Challenge.git
   ```

2. Navigate to the directory:
   ```bash
   cd Fix_My_Code_Challenge
   ```

3. Identify and fix the issues in the provided code.

4. Test your fixes to ensure the code runs correctly.

### Task 0: FizzBuzz
**Current Issue:**
The output for 15 should be "FizzBuzz", but it is currently "Fizz".

**How to Use:**
1. Ensure Python is installed on your system.
2. Run the script with a number as the argument:
   ```bash
   python3 0-fizzbuzz.py 50
   ```
3. Verify the output. For example, 15 should be "FizzBuzz".


### Task 1: Print Square
**Current Issue:**
The output does not correctly represent the square for sizes larger than 4.

**How to Use:**
1. Ensure Node.js is installed on your system.
2. Run the script with a number as the argument:
   ```bash
   node 1-print_square.js 4
   ```
3. Verify that the output is a square grid of `#` characters. For size 10, it should print a 10x10 grid.


### Task 2: Sort
**Current Issue:**
The script currently does not sort numbers and strings correctly.

**How to Use:**
1. Ensure Ruby is installed on your system.
2. Run the script with a list of arguments:
   ```bash
   ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
   ```
3. Verify that the output is sorted correctly. Numerical values should be in ascending order, followed by strings.


### Task 3: User Password
**Current Issue:**
The script does not correctly validate the password.

**How to Use:**
1. Ensure Python is installed on your system.
2. Run the script without arguments:
   ```bash
   python3 3-user.py
   ```
3. Ensure the output indicates whether the password is valid. No errors should be printed if the script is functioning correctly.

### Task 4: Double Linked List
**Current Issue:**
The linked list operations are not functioning as expected, particularly the deletion of nodes.

**How to Use:**
1. Ensure GCC is installed on your system.
2. Compile the source code:
   ```bash
   gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
   ```
3. Run the compiled program:
   ```bash
   ./delete_dnodeint
   ```
4. Verify the output to ensure that nodes are added and deleted correctly from the linked list.


## Tasks
### 0. FizzBuzz
**#advanced**

Fix the implementation of FizzBuzz in Python.  
**Source Code:** [0-fizzbuzz.py]([0-fizzbuzz.py](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/0-fizzbuzz.py)) 

```shell
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```
15 should print FizzBuzz not Fizz.

### 1. Print square
**#advanced**

Fix the implementation of printing a square in JavaScript.  
**Source Code:** [1-print_square.js](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/1-print_square.js) 

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
**Source Code:** [2-sort.rb](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/2-sort.rb)

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
**Source Code:** [3-user.py]([3-user.py](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/3-user.py))

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
**Source Code:** [4-delete_dnodeint]([4-delete_dnodeint](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/tree/master/4-delete_dnodeint))

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

