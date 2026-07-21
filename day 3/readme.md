PROBLEM STATEMENT:

You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list.

ALGORITHM:

STEP 1: initialize an empty set, left = 0, and maxLength = 0.
STEP 2: Traverse the string using the right pointer.
STEP 3: Remove duplicate characters by moving the left pointer.
STEP 4: Add the current character to the set.
STEP 5: Update the maximum substring length.
STEP 6: Return maxLength.