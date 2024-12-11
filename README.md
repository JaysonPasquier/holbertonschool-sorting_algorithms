# Sorting algorithms & Big O
## Description
This project implements several sorting algorithms in C, including Bubble Sort, Insertion Sort, Selection Sort, and Quick Sort. Each algorithm is designed to sort arrays of integers in ascending order and includes functionality to print the array after each swap.
Files and Functions
## Sorting Algorithms
#### Bubble Sort
- File: 0-bubble_sort.c
- Prototype: void bubble_sort(int *array, size_t size);
> Description: Sorts an array using the Bubble Sort algorithm. Prints the array after each swap.
#### Insertion Sort
- File: 1-insertion_sort_list.c
- Prototype: void insertion_sort_list(listint_t **list);
 > Description: Sorts a doubly linked list using the Insertion Sort algorithm. Prints the list after each swap.
#### Selection Sort
- File: 2-selection_sort.c
- Prototype: void selection_sort(int *array, size_t size);
> Description: Sorts an array using the Selection Sort algorithm. Prints the array after each swap.
#### Quick Sort
- File: 3-quick_sort.c
- Prototype: void quick_sort(int *array, size_t size);
> Description: Sorts an array using the Quick Sort algorithm with Lomuto partition scheme. Prints the array after each swap.
## Utility Functions
 * Print Array
> File: print_array.c
> Prototype: void print_array(const int *array, size_t size);
>Description: Prints an array of integers.
- Print List
>File: print_list.c
>Prototype: void print_list(const listint_t *list);
>Description: Prints a doubly linked list of integers.
## Data Structures
Doubly Linked List Node
c
typedef struct listint_s {
    const int n;
    struct listint_s *prev;
    struct listint_s *next;
} listint_t;
## Compilation
To compile the project, use:
```bash
gcc -Wall -Wextra -Werror -pedantic *.c -o sorting_algorithms
```
## Usage
Include the header file sort.h in your C files and link with the compiled object files. Each sorting function can be tested using provided main files (e.g., 0-main.c, 1-main.c, etc.).
Complexity Notations
For each sorting algorithm, create a file with Big O notations of time complexity:
Best Case
Average Case
Worst Case
- Example for Bubble Sort:
File: 0-O
text
O(n)
O(n^2)
O(n^2)
## Author
[Sayne667](https://github.com/Saynez667)
[JaysonPasquier](https://github.com/JaysonPasquier)