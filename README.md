DAY 1:
PROBLEM STATEMENT:
Given an array of integers nums and an integer target, return the indices of the two numbers such that they add up to the target.

DESCRIPTION:
The Two Sum problem is used to find two numbers in an array whose sum is equal to a given target value. This solution uses a dictionary (hash map) to store the numbers that have already been visited along with their indices. For each number, it checks whether its required complement is already present in the dictionary. If found, it returns the indices of the two numbers; otherwise, it stores the current number and continues searching.

ALGORITHM:
STEP 1: Create an empty dictionary called seen.
STEP 2: Traverse the array using a loop.
STEP 3: For each element, calculate the complement as target - current number.
STEP 4: Check if the complement exists in the dictionary.
STEP 5: If it exists, return the indices of the complement and the current element.
STEP 6: Otherwise, store the current number and its index in the dictionary.
STEP 7: Repeat until the required pair is found.

CODE:
<img width="438" height="234" alt="image" src="https://github.com/user-attachments/assets/45897a51-2fc0-40ae-bd38-bbc8cd56abd8" />

OUTPUT:
<img width="632" height="266" alt="image" src="https://github.com/user-attachments/assets/83329585-71cc-48c9-a0fb-aceea9fb8900" />

DAY 2:
PROBLEM STTEMENT:

Given a signed 32-bit integer x, return x with its digits reversed. If reversing x causes the value to go outside the signed 32-bit integer range [-231, 231 - 1], then return 0.

DESCRIPTION:

This program reverses the digits of a 32-bit signed integer while checking for integer overflow. If the reversed number exceeds the valid range, it returns `0`; otherwise, it returns the reversed integer.

ALGORITHM:

STEP 1: Start.
STEP 2: Initialize rev = 0.
STEP 3: Repeat until x becomes 0:
STEP 4: Find the last digit using x % 10.
STEP 5: Remove the last digit using x / 10.
STEP 6: Check for 32-bit integer overflow.
STEP 7: Update the reversed number: rev = rev * 10 + digit.
STEP 8: If overflow occurs, return 0.
STEP 9: Return the reversed number rev.

DAY 3:

DESCRIPTION:
This program adds two numbers represented as linked lists. Each node contains one digit, and the digits are stored in reverse order. It adds the digits one by one, handles the carry when the sum is greater than 9, and creates a new linked list to store the result.

ALGORITHM:

STEP 1: Create a dummy node to store the result.
STEP 2: Initialize carry as 0.
STEP 3: Traverse both linked lists until both lists and the carry become empty.
STEP 4: Add the current digits from both lists along with the carry.
STEP 5: Store the last digit of the sum in a new node.
STEP 6: Update the carry with the remaining value.
STEP 7: Move to the next nodes in both linked lists.
STEP 8: Return the linked list starting from dummy.next.