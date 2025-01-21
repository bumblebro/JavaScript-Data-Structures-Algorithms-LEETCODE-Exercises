# Big O Notation: Greek Letters and Their Meanings

## Overview

When dealing with Big O notation, you'll encounter three important Greek letters:
- **Omega (Ω)**
- **Theta (Θ)**
- **Omicron (O)**

Out of these, **Omicron** is better known as **Big O**, which is the one you'll encounter most often in coding and technical interviews.

## Understanding the Greek Letters

These Greek letters are used to describe the performance of algorithms in different scenarios. Let’s break down their use with an example:

### Example: Searching an Array

Imagine you are building a **for loop** to iterate through an array until you find a particular number.

- **Best Case**: This is when the number you are looking for is found in the first iteration. In this case, the number of iterations is minimized. This scenario is represented by **Ω (Omega)**.
  
- **Average Case**: This represents the average number of iterations it takes to find the number in an array. This case is represented by **Θ (Theta)**.
  
- **Worst Case**: This is when the number you're looking for is not present in the array, or it's found at the last position. This is the scenario where the algorithm has to iterate through the entire array. This case is represented by **O (Omicron)** or **Big O**.

## Big O: Worst Case Scenario

- **Big O** (O) always refers to the **worst-case scenario**. This is the focus of Big O notation, which is why you often hear terms like "What's the worst-case Big O?" during interviews.
- **Best Case and Average Case** are not measured by Big O; instead, they are represented by **Omega (Ω)** and **Theta (Θ)**, respectively.

### Summary of Greek Letters

- **Ω (Omega)**: Best case scenario.
- **Θ (Theta)**: Average case scenario.
- **O (Omicron/Big O)**: Worst case scenario.

## Conclusion

- When you're asked about Big O in interviews or coding, you’re always referring to the worst-case scenario.
- Understanding the differences between Omega, Theta, and Big O will help you describe the efficiency of algorithms in various contexts.
