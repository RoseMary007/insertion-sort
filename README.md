# Insertion Sort Algorithm

## Objective
Implement the Insertion Sort algorithm and analyze its time and space complexities.

## Programming Language
Python

## Algorithm
1. Start from the second element.
2. Store the current element as the `key`.
3. Compare the key with previous elements.
4. Shift larger elements one position to the right.
5. Insert the key at the correct position.
6. Repeat until the array is sorted.

## How to Run
1. Install Python 3.
2. Open the terminal.
3. Execute the following command:

   ```bash
   python insertion_sort.py
   ```

4. Enter the number of elements.
5. Enter the array elements.
6. View the sorted output.

## Sample Input

```text
6
64
25
12
22
11
90
```

## Sample Output

```text
Enter number of elements: 6
Enter the elements:
64
25
12
22
11
90
Sorted Array:
11 12 22 25 64 90
```

## Time Complexity

| Case | Big O | Theta (Θ) | Omega (Ω) |
|---|---|---|---|
| Best Case | O(n) | Θ(n) | Ω(n) |
| Average Case | O(n²) | Θ(n²) | Ω(n²) |
| Worst Case | O(n²) | Θ(n²) | Ω(n²) |

## Space Complexity

- **O(1)** – Insertion Sort is an in-place sorting algorithm that requires constant auxiliary space.

## Advantages
- Simple to implement.
- Efficient for small datasets.
- Stable sorting algorithm.
- In-place sorting algorithm.

## Disadvantages
- Inefficient for large datasets.
- Average and worst-case time complexity is O(n²).

## Course Outcome
**CO1** – Analyze any given algorithm and express its time and space complexities using asymptotic notations.
