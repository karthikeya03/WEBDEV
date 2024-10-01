# DarwinBox Hiring Process

## 1. Coding Contest
- **Duration**: 1 hour
- **Structure**: 
  - 12 MCQs 
  - 2 Coding Questions
- **Cutoff**: 
  - You need to solve **1.5 coding questions** and score **at least 5 points** from the MCQs to qualify.
- **Difficulty**: 
  - Questions vary between **easy** to **medium** (1400-1500 Codeforces rating).
- **Example Problem**: *Longest Palindromic Subsequence*.

## 2. Technical Interview (50 min - 1 hr)
- **Topics Covered**: 
  - **Introduction**: Background, technologies you've worked with.
  - **Technologies**: Focus on tech stack, e.g., C++, SQL/Database, front-end (React), and back-end (Django).
  - **Problem-Solving**: 
    - Explain how you solved the coding questions from the contest.
    - Expect follow-up questions on your approach and algorithm.
  - **Company Requirements**: Basic understanding of **JavaScript** (even if it’s not your primary language).
  - **Hands-on Tasks**: 
    - **Pen and Paper**: You may be asked to explain algorithms or write **pseudo-code**.
    - Basic **JavaScript** coding (no SQL queries required).

## 3. HR Interview (45 minutes)
- **Purpose**: General behavioral questions, cultural fit, and final screening.
- **Timeline**: Results are usually announced within **1-2 days**.

### Final Selection
- Out of **18 candidates**, only **3** were selected.

---

# DarwinBox Previous Interview Questions

## Question 1: Bomb Explosion in a Matrix
**Problem**:  
Given an `m × n` matrix where each cell represents either an empty space (`0`), a wall (`1`), or a bomb (`B`), write a function to calculate the maximum area that can be affected by a bomb explosion. The bomb explosion can spread in all four directions (up, down, left, right), but the explosion cannot pass through walls (`1`). Return the maximum area affected by a single bomb.

**Approach**:
1. **Traversal**: Perform a BFS or DFS from the bomb's location.
2. **Constraints**: The explosion stops when it encounters a wall (`1`).
3. **Efficiency**: Use a visited matrix to avoid redundant calculations.



![1.1](C:\Users\saisa\Desktop\1.1.png)



## Question 2: Subarray with Target Sum
**Problem**:  
Given an integer array `arr[]`, an integer `K` representing the length of a subarray, and an integer `target` representing the target sum, write a Java function that finds a subarray of length `K` such that the sum of the elements in the subarray is equal to `target`. If multiple subarrays satisfy this condition, return the first one. If no such subarray exists, return an empty array.

**Approach**:
1. **Sliding Window**: Use a sliding window technique to maintain a subarray of size `K` and calculate the sum dynamically.
2. **Time Complexity**: O(n), where `n` is the size of the array.



![2.2](C:\Users\saisa\Desktop\2.2.png)

## Question 3: Subset String Problem
**Problem**:  
Given two strings `str1` and `str2` where `str1` is guaranteed to be greater than or equal to `str2` in length, write a function to determine if `str2` is a subset of `str1`. The function should return true if all the characters of `str2` are present in `str1` in any order, otherwise return false. The characters in `str2` must all appear in `str1`, but their order does not matter.

**Approach**:
1. **HashMap or Frequency Array**: Count the occurrences of each character in `str1` and `str2`. Ensure `str1` has at least as many occurrences of each character as `str2`.
2. **Time Complexity**: O(n) where `n` is the length of `str1`.



![3.2](C:\Users\saisa\Desktop\3.2.png)

---

## Additional Insights:
1. **Preparation Tips**: 
   - Focus on **problem-solving skills** (BFS, DFS, sliding window, dynamic programming).
   - Practice questions of **medium difficulty** on platforms like Codeforces or LeetCode.
2. **Language and Technology**: 
   - Even though your primary language may be **C++**, it's good to brush up on **JavaScript basics** as DarwinBox may require you to work with front-end technologies.
   - For the backend, familiarity with **Django** is a plus, but being adaptable to other frameworks is equally important.
3. **Behavioral Interview**: For the HR interview, focus on **soft skills** and cultural alignment with the company. This is crucial for companies like DarwinBox, which emphasize teamwork and adaptability.
