# Reflection – AI Number Program Lab

##  Student Name:
Zeigler, Austin G.

##  GitHub Repository Link:
(https://github.com/azeigler97/unit8_lab2)

## Iteration 1

What the AI code does:
- The AI generated a basic summation method that loops through the array elements and returns their total sum.

Tests passed/failed:
- The basic tests with standard positive integer arrays passed, but tests expecting the maximum value or handling empty arrays failed because the logic only calculates a cumulative sum instead of finding a maximum.

What surprised you:
- The AI provided a general summation logic rather than an operation searching for a peak value, showing that vague initial prompts default to basic accumulator patterns.

Commit message:
- Iteration 1: AI-generated implementation

---

## Iteration 2

What changed:
- Replaced the summation logic with a maximum-value tracking algorithm using a prompt specifically asking for the largest integer in an array.

What improved:
- Standard test cases evaluating populated arrays for their maximum value now pass successfully.

What still failed and why:
- Tests involving an empty array still fail or throw an `ArrayIndexOutOfBoundsException` because the code accesses `values[0]` without checking if the array length is zero.

Commit message:
- Iteration 2: largest value implementation

---

## Iteration 3

Final behavior:
-

What was fixed:
-

What you learned:
-

Commit message:
-

---

## Final Reflection

- How did AI responses change across prompts?
- How did testing affect your changes?
- What did version control help you understand?