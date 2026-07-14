# Algorithms in C#

A collection of algorithm implementations and coding challenge solutions written in **C#**.

This repository is designed to improve problem-solving skills, strengthen data structure knowledge, and prepare for technical interviews by practicing common algorithms and patterns.

## Topics Covered

- Arrays
- Strings
- Two Pointers
- Sliding Window
- Binary Search
- Recursion
- Sorting Algorithms
- Searching Algorithms
- Hash Tables
- Stack
- Queue
- Linked List
- Trees
- Binary Search Trees (BST)
- Graphs
- Heap / Priority Queue
- Dynamic Programming
- Greedy Algorithms
- Backtracking
- Bit Manipulation
- Math

## Repository Structure

```
Algorithms/
│
├── Array/
├── String/
├── BinarySearch/
├── Sorting/
├── Recursion/
├── Stack/
├── Queue/
├── LinkedList/
├── Tree/
├── Graph/
├── DynamicProgramming/
├── Greedy/
├── Backtracking/
└── ...
```

## Example

```csharp
public int BinarySearch(int[] nums, int target)
{
    int left = 0;
    int right = nums.Length - 1;

    while (left <= right)
    {
        int mid = left + (right - left) / 2;

        if (nums[mid] == target)
            return mid;

        if (nums[mid] < target)
            left = mid + 1;
        else
            right = mid - 1;
    }

    return -1;
}
```

## Goals

- Improve algorithmic thinking.
- Master common interview patterns.
- Write clean and efficient C# code.
- Understand time and space complexity.
- Build a strong problem-solving portfolio.

## Complexity Analysis

Whenever possible, each solution includes:

- Time Complexity: **O(...)**
- Space Complexity: **O(...)**

## Platforms

Problems are solved from platforms such as:

- LeetCode
- HackerRank
- Codeforces
- GeeksforGeeks
- CodingBat

## Technologies

- C#
- .NET
- Visual Studio
- Git & GitHub

## Contributing

Suggestions and improvements are always welcome. Feel free to fork the repository, open an issue, or submit a pull request.

## License

This project is open source and available under the MIT License.
