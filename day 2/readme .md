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