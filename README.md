Siddhant Arora

24070123107

ENTC B1

# A) Array Operations in C++

This document provides a comprehensive overview of five C++ programs that demonstrate fundamental array operations. Each section includes the theory behind the program, the algorithm used, sample output, and a conclusion summarizing its purpose and behavior.

---

## 1. Input and Display 10 Numbers

### Theory
This program reads 10 integers from the user and displays them. It demonstrates basic array usage and input/output operations in C++.

### Algorithm
1. Declare an array of size 10.
2. Use a loop to read 10 integers from the user.
3. Use another loop to display the entered integers.

### Output
Enter 10 numbers: 1 2 3 4 5 6 7 8 9 10 

You entered: 1 2 3 4 5 6 7 8 9 10

### Conclusion
This program effectively demonstrates how to store and retrieve multiple values using arrays and loops.

---

## 2. Sum, Average, Max, and Min of Array Elements

### Theory
This program calculates the sum, average, maximum, and minimum of 6 integers entered by the user. It uses conditional statements to track the max and min values.

### Algorithm
1. Declare an array of size 6.
2. Initialize `sum`, `max`, and `min`.
3. Read 6 integers and update `sum`, `max`, and `min` accordingly.
4. Calculate average as `sum / 6`.
5. Display all results.

### Output
Enter 6 numbers: 1 2 3 4 5 6

Array elements: 1 2 3 4 5 6 

Sum: 21 

Average: 3.5 

Max: 6 Min: 1

### Conclusion
This program demonstrates how to perform basic statistical operations on array data using loops and conditionals.

---

## 3. Reverse an Array

### Theory
This program reverses the order of elements in an array. It uses a two-pointer approach to swap elements from both ends.

### Algorithm
1. Read the number of elements (`num`).
2. Input `num` elements into an array.
3. Use a loop to swap elements from start and end moving toward the center.
4. Display the reversed array.

### Output
Enter total count: 4 

Element 1: 56 

Element 2: 87 

Element 3: 32 

Element 4: 56

Reversed array: 56 32 87 56

### Conclusion
This program illustrates how to reverse an array in-place using a simple swapping technique.

---

## 4. Search for an Element in an Array

### Theory
This program performs a linear search to find a specific value in a predefined array. It reports the index if found.

### Algorithm
1. Declare and initialize an array.
2. Read the search key from the user.
3. Traverse the array and compare each element with the key.
4. If found, display the index; otherwise, report not found.

### Output
nter the number you want to search for: 6 

Key found at location: 6

### Conclusion
Linear search is a straightforward method for finding elements in an unsorted array. This program demonstrates its implementation.

---

## 5. Sum and Average with Logical Error

### Theory
This program attempts to calculate the sum and average of 6 integers but contains a logical error: `sum` is not initialized, and `average` is calculated before `sum` is computed.

### Algorithm
1. Declare an array of size 6.
2. Declare `sum` but do not initialize it.
3. Calculate `average = sum / 6` before computing `sum`.
4. Read 6 integers and compute `sum`.
5. Display `sum` and `average`.

### Output
The numbers of array are: 1 2 3 4 5 6 1 2 3 4 5 6 

The sum of elements of array are: 21 

The average of elements of array are: 0

### Conclusion
This program highlights the importance of initializing variables and computing dependent values in the correct order. The average is incorrectly calculated due to premature evaluation.

---
# B) String Operations in C++

This document describes multiple C++ programs that demonstrate various operations on strings, including input/output, reversing a string, checking for a palindrome, and concatenating names.

---

## 1. Palindrome Check

### Theory
A palindrome is a word, phrase, number, or sequence that reads the same backward as forward. This program takes a string input from the user and checks whether it is a palindrome.

### Algorithm
1. Read a string from the user.
2. Reverse the string using a loop.
3. Compare the reversed string with the original.
4. Display whether the string is a palindrome.

### Output

Enter a string: b

The string is a palindrome

### Conclusion
This program successfully checks whether a given string is a palindrome using basic string manipulation techniques.

---

## 2. Concatenation of String

### Theory
String concatenation is the operation of joining character strings end-to-end. This program reads a first name and a last name from the user and combines them into a full name.

### Algorithm
1. Read first name and last name.
2. Concatenate them using the `+` operator.
3. Display the full name.

### Output

Enter first name: Siddhant 

Enter last name: Arora
Full name : Siddhant Arora

### Conclusion
This program demonstrates how to use string concatenation in C++ to combine two separate inputs into a meaningful full name.

---

## 3. Display User Input String

### Theory
Reading and displaying strings is a basic operation in any programming language. This program takes a string input and displays it.

### Algorithm
1. Read a word (string) from the user.
2. Display the word.

### Output

Enter a Name: Siddhant 

You entered: Siddhant

### Conclusion
This program demonstrates a simple input/output operation using C++ strings.

---

## 4. Reverse a String

### Theory
String reversal is a basic manipulation operation where the characters of the string are rearranged from end to start.

### Algorithm
1. Read a string from the user.
2. Use a loop to reverse the string.
3. Display the reversed string.

### Sample Output

Enter total count: 2
Element 1: 1234
Element 2: 56789
Original array: 1234 56789 
Reversed array: 56789 1234

### Conclusion
This program shows how to reverse a string manually using loops in C++.

---
