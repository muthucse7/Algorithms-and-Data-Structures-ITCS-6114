# Sorting Algorithms Performance Comparison

This project implements and compares the performance of several comparison-based sorting algorithms using Python.

## Implemented Sorting Algorithms

- Insertion Sort
- Merge Sort
- Heap Sort
- In-Place Quicksort
- Modified Quicksort (using median-of-three as pivot and insertion sort for small subproblems)

## Data Structures Used

- Arrays
- Integers
- Strings (potentially)

## Complexity Analysis

- **Insertion Sort:** Average/Worst case: O(n²), Auxiliary Space: O(1)
- **Merge Sort:** Time complexity: O(nlogn), Auxiliary Space: O(n)
- **Heap Sort:** Time complexity: O(nlogn), Auxiliary Space: O(1)
- **Quick Sort (In-Place):** Average: O(nlogn), Worst case: O(n²), Auxiliary Space: O(n)
- **Modified Quick Sort:** Average: O(nlogn), Worst case: O(n²), Auxiliary Space: O(n)

## Execution Instructions

### Prerequisites

- Python 3.x
- matplotlib for plotting graphs

### Setup

Clone the repository:

```bash
git clone https://github.com/your-username/sorting-algorithms-comparison.git
cd sorting-algorithms-comparison

Install required packages:

pip install matplotlib
Running the Project
Ensure the following steps are included in a single Python file (e.g., sort_performance.py):

Import necessary libraries.
Implement the sorting algorithms (Insertion Sort, Merge Sort, Heap Sort, In-Place Quicksort, Modified Quicksort).
Generate input data and measure execution time.
Plot the results.
Measure performance on already sorted and reversely sorted arrays.

python project1.py

Viewing the Output
The script will display a plot comparing the performance of different sorting algorithms.
It will also print the execution times for sorted and reversely sorted arrays in the terminal.

Conclusion
Based on the analysis, Merge Sort, Heap Sort, and Quick Sort generally perform better than Insertion Sort for larger input sizes. Modified Quick Sort improves the performance of Quick Sort for smaller subproblems by using Insertion Sort for small subarrays. The choice of sorting algorithm can significantly impact performance depending on the input size and characteristics. ```


