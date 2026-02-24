# PYTHON-EXP-7

# Study of For Loop and While Loop in Python

## Aim

To understand and implement the working of `for` and `while` loops in Python programming.

---

## Objectives

- To learn the concept of repeated (iterative) execution  
- To create and execute loops for basic iteration  
- To apply loop control statements such as `break` and `continue`  
- To differentiate between sequence-based and condition-based loops  

---

## Theory

Looping is a control structure in programming that enables a block of code to run multiple times, either for a fixed number of iterations or until a specified condition becomes false. Python mainly provides two looping constructs:

- `for` loop  
- `while` loop  

---

### 1. For Loop

The `for` loop in Python is used to iterate over elements of a sequence such as a list, tuple, dictionary, set, or string. It automatically traverses through each item in the collection and executes a block of statements for every element.

It is most suitable when the number of iterations is already known or when working directly with iterable objects.

---

### 2. While Loop

The `while` loop executes a block of code repeatedly as long as a given condition evaluates to `True`. This loop is generally used when the total number of iterations is not predetermined and depends on a logical condition.

The loop must include a condition update inside it to prevent infinite execution.

---

## Difference Between For Loop and While Loop

- A `for` loop is preferred when the number of iterations is known in advance.  
- A `while` loop is used when execution depends on a condition.  
- The `for` loop automatically handles iteration over sequences.  
- The `while` loop requires manual updating of loop variables.  

---

## Features of Loops

- **Iterative Execution** – Repeats code blocks to process data efficiently.  
- **Controlled Flow** – Directs execution based on defined conditions.  
- **Reduced Redundancy** – Eliminates repetitive code writing.  
- **Automation** – Commonly used in mathematical computations and data processing tasks.  

---

## Break Statement

The `break` statement is used to immediately terminate a loop.  
When encountered, the loop stops executing and control moves to the statement following the loop.  
It is often combined with an `if` condition.

---

## Continue Statement

The `continue` statement skips the remaining code in the current iteration and proceeds directly to the next iteration of the loop.  
Unlike `break`, it does not terminate the loop entirely.

---

## Applications of Loops

- Processing student or database records  
- Accessing configuration data  
- Removing duplicates or filtering collections  
- Performing repetitive calculations  
- Automating data-related tasks  

---

## Algorithms

### 1. Factorial of a Number

**Start**

1. Initialize `i = 1` and `fac = 1`  
2. Input the number `n`  
3. While `i <= n`  
   - Multiply `fac = fac * i`  
   - Increment `i` by 1  
4. Display the value of `fac`  

**Stop**

---

### 2. Reverse a Number

**Start**

1. Input the number `a`  
2. Initialize `rev = 0`  
3. While `a > 0`  
   - `dig = a % 10`  
   - `rev = (rev * 10) + dig`  
   - `a = a // 10`  
4. Display `rev`  

**Stop**

---

### 3. Count Digits in a Number

**Start**

1. Input the number `n`  
2. Initialize `count = 0`  
3. While `n > 0`  
   - Increment `count`  
   - Remove last digit using `n //= 10`  
4. Display `count`  

**Stop**

---

### 4. Armstrong Number Check

**Start**

1. Input number `N` as a string  
2. Initialize `total = 0`  
3. For each character in `N`  
   - Convert it to integer  
   - Raise it to the power of length of `N`  
   - Add result to `total`  
4. If `total` equals integer value of `N`  
   - Print "It is an Armstrong Number"  
   Else  
   - Print "It is not an Armstrong Number"  

**Stop**

---

### 5. All Possible Combinations of 3 Digits

**Start**

1. Input a three-digit number `N`  
2. Extract digits into a list `d`  
3. Use three nested loops (i, j, k from 0 to 2)  
4. Check that `i`, `j`, and `k` are all different  
5. Print `d[i], d[j], d[k]`  

**Stop**

---

## Conclusion

Loops are essential programming tools that help execute repetitive tasks efficiently.  
The `for` loop is best suited for working with sequences, while the `while` loop is ideal for condition-based execution.  
By using control statements like `break` and `continue`, programmers can precisely manage loop execution, making loops highly useful in real-world applications.
