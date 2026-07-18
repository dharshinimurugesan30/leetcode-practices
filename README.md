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
