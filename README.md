# Sum-of-the-Given-Numbers

Input:3 8 11 25 

Output: 44 

Question: Sum of the Given Numbers

Given an integer N, write a program which reads N inputs and prints the sum of the given input integers.

Approach:

To solve this problem, we will follow these steps:

Read the number of inputs (N) from the user.

Initialize variables for counting and sum.

Read the input numbers one by one and calculate the sum.

Print the sum of the input numbers.

Step-by-Step Explanation:

Step 1: Read the number of inputs

First, we need to read the number of inputs (N) from the user. We can use the input() function to read the input and int() to convert it into an integer.

Step 2: Initialize variables for counting and sum

Next, we need to initialize two variables: one for counting the number of inputs we have read so far (counter) and another for storing the sum of the input numbers (sum). We will set both variables to 0 initially.

Step 3: Read the input numbers and calculate the sum

Now, we will use a while loop to read the input numbers one by one. The loop will continue until the counter is less than number_of_inputs. Inside the loop, we will:

Read an input number using the input() function and convert it to an integer using int().
Add the input number to the sum.
Increment the counter by 1.

Step 4: Print the sum

Finally, after the loop is finished, we will print the sum of the input numbers using the print() function.

