# Python LeetCode – Basic Problem Set

This repository contains a few beginner-friendly LeetCode problems. These questions help build confidence with arrays, loops, and basic logic. Each problem is simple, clear, and great for improving problem-solving skills step-by-step.

## 1️⃣ 1431. Kids With the Greatest Number of Candies

- For each kid, check if giving them extra candies makes them have the most candies.

- Helps understand comparing values in an array.

- Returns a list of true/false based on who can reach the maximum.

## 2️⃣ 1480. Running Sum of 1D Array

- Calculates the running total of numbers from left to right.

- Helps practice loops and keeping track of a growing sum.

- Great for understanding how prefix sums work.

## 3️⃣ 1470. Shuffle the Array

- Mixes two halves of an array into an alternating pattern.

- Builds understanding of index handling and rearranging lists.

- Very useful for practicing basic array manipulation.
  

## 1️⃣ Number of Good Pairs
### Step-by-step explanation

- You are given an array of integers called nums.

- You need to look at two different positions in the array at a time.

- For each pair of positions (i, j), check that i < j.

- Compare the values at those positions: nums[i] and nums[j].

- If both values are equal, then that pair is called a good pair.

- Count all such good pairs and return the total count.
  
## 2️⃣ Find Numbers with Even Number of Digits
### Step-by-step explanation

- You are given a list (array) of integers.

- Take one number at a time from the list.

- Count how many digits that number contains.

- Check whether the digit count is an even number.

- Keep a running count of all numbers that have an even number of digits.

- After checking all the numbers, return the final count.

## 3️⃣ Number of Good Pairs
### Step-by-step explanation

- You are given a list of integers.

- Pick one number and compare it with the numbers that come after it in the list.

- For each comparison, check whether both numbers are equal.

- Make sure the index of the first number is smaller than the index of the second number.

- If both conditions are satisfied, consider it a valid (good) pair.

- Count all such valid pairs and return the total count.


## 4️⃣ How Many Numbers Are Smaller Than the Current Number
### Step-by-step explanation

- You are given a list of integers.

- Pick one number from the list.

- Compare this number with all other numbers in the list.

- Count how many numbers are smaller than the current number.

- Store this count in the result list at the same position.

- Repeat the process for every number and return the final list of counts.

## 5️⃣ Subtract the Product and Sum of Digits of an Integer
### Step-by-step explanation

- You are given a single integer number.

- Break the number into its individual digits.

- Calculate the product of all the digits.

- Calculate the sum of all the digits.

- Subtract the sum of the digits from the product of the digits.

- Return the final result.

## 6️⃣ XOR Operation in an Array
### Step-by-step explanation

- You are given two integers: n and start.

- Create an array with length n.

- For each index i, calculate the value using the formula start + 2 × i.

- Store each calculated value in the array.

- Apply the XOR operation between all the elements of the array.

- Return the final XOR result.

## 1️⃣ 1464. Maximum Product of Two Elements in an Array

- Difficulty: Easy

### Problem Statement:
- Given an integer array nums, choose two different indices i and j and return the maximum value of
(nums[i]−1)∗(nums[j]−1)


### Core Idea:

- Identify the two largest elements in the array

- Subtract 1 from each

- Compute the product

### Key Skills Demonstrated:

- Greedy selection

- Array scanning

- Optimization without sorting

## 2️⃣ 1395. Count Number of Teams

- Difficulty: Medium

### Problem Statement:
- Given unique soldier ratings, count the number of valid teams of size 3 such that:

- Ratings are strictly increasing or

- Ratings are strictly decreasing with indices i < j < k.

### Core Idea:

- Fix a middle soldier

- Count smaller and larger elements on both sides

- Combine counts to form valid triplets

### Key Skills Demonstrated:

- Nested iteration with constraints

- Combinatorial counting

- Pattern recognition (increasing vs decreasing sequences)

## 3️⃣ 1450. Number of Students Doing Homework at a Given Time

- Difficulty: Easy

### Problem Statement:
- Given startTime, endTime, and queryTime, return how many students are doing homework at queryTime.

### Core Idea:

- Iterate through students

- Check if queryTime lies in the inclusive interval


### Key Skills Demonstrated:

- Interval validation

- Linear scanning

- Condition-based counting

## 4️⃣ 1342. Number of Steps to Reduce a Number to Zero

- Difficulty: Easy

### Problem Statement:
- Reduce a number to zero using:

- Divide by 2 if even

- Subtract 1 if odd
  
- Return the number of steps.

### Core Idea:

- Repeatedly apply rules until the number becomes zero

- Maintain a step counter

### Key Skills Demonstrated:

- Loop control

- Even/odd logic

- Simulation-based problem solving

## 5️⃣ 338. Counting Bits

- Difficulty: Easy

### Problem Statement:
- For a given integer n, return an array where each index i contains the count of 1s in the binary representation of i.

### Core Idea:

- Build results incrementally from 0 to n

- Leverage previous computations (dynamic programming)

### Key Skills Demonstrated:

- Bit manipulation

- Dynamic programming mindset

- Binary number understanding

### 🛠️ Tech Stack

- Language: Python

- Paradigm: Iterative, Greedy, Dynamic Programming

### Complexity Focus:

- Time: O(n), O(n²) where required

- Space: Optimized, minimal auxiliary usage


## ▶️ How to Use
- Pick any problem from the list.

- Read the short explanation.

- Check or write your solution inside the solutions/ folder.
