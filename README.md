# Company Logo – Python

Solution for the HackerRank **Company Logo** problem.

## Problem
Given a string, find the top three most common characters.
- Sort by descending frequency
- If frequencies are equal, sort alphabetically

## Approach
- Use `collections.Counter` to count characters
- Sort using a custom key `(-count, character)`
- Print the top three results

## Example
Input:
aabbbccde

Output:
b 3
a 2
c 2
