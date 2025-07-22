LeetCode Solutions

Overview

This is my LeetCode problems and solutions (hopefully) where I will be posting. Below shows the projects directories, the files, and the corresponding README files. 

Repository Structure

The solutions are organized in a main directory with subdirectories for each problem, each containing the solution code and relevant documentation.

LeetCode-Solutions/
├── arrays/
│   ├── two_sum/
│   │   ├── solution.py
│   │   ├── README.md
│   └── palindrome_number/
│       ├── solution.py
│       ├── README.md
├── strings/
│   └── valid_parentheses/
│       ├── solution.py
│       ├── README.md
└── README.md

f
Main Directory: Contains subdirectories categorized by problem type (e.g., arrays, strings).



Problem Subdirectories: Each includes:





solution.py: The Python solution with comments explaining the logic, time/space complexity, and approach.



README.md: Problem description, approach, and any optimizations or trade-offs.

Goals





Apply Python skills from CS50P to solve algorithmic problems.



Demonstrate clean, readable, and efficient code following PEP 8 standards.



Showcase problem-solving strategies, including brute force and optimized approaches.



Build a portfolio to support my transition to software engineering.

How to Use





Navigate to a problem’s subdirectory to view its solution and README.



Each solution includes:





Problem Statement: A brief description or link to the LeetCode problem.



Approach: Explanation of the logic and any optimizations.



Complexity: Time and space complexity analysis.



Code: Well-commented Python code for clarity.

Example:

# two_sum/solution.py
# Time: O(n) using hash map
# Space: O(n) for hash map
def twoSum(nums: list[int], target: int) -> list[int]:
    num_dict = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in num_dict:
            return [num_dict[complement], i]
        num_dict[num] = i
    return []


Skills Demonstrated: Variables, control flow, functions, data structures (lists, dictionaries, sets), and algorithmic thinking.

Contact

Feel free to explore the solutions and provide feedback! Connect with me on LinkedIn or check out my other projects on GitHub