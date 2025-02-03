# 30 Days Of Code
The goal of this repository is to serve as a log of all the coding done for 30 days. This is a self-challenge to elevate my knowledge of software engineering with anything related to coding wether it is Leetcode style problems, personal projects, or learning a new language or technology. I will update this log daily with what I have completed and general notes on the subject. 

## Day 1 - 2025/02/03
### Non-Coding
I decided to start Leetcode from scratch to refresh/relearn important concepts. I created a document with the most important coding problem topic, data structures, algorithms, and a study schedule for al the topics.

### Coding
I completed the Leetcode problem 'Two Sum'. In this problem you have to find 2 numbers in a given list that the sum equals to the given target. For the solution of this problem I used a hashmap. First I would calculate the complement by using the target minus the current number in the list. If the complement exists in the hashmap you can return the current index and the index of the stored number in the hashmap. If not, add the number and index in the hashmap. 

This has a worst case complexity of O(n) since one of the two numbers could be at the end. Space complexity is O(n).
