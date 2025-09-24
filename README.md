# linked-lists-in-cpp-

## What is a Linked List?

A **linked list** is a fundamental data structure used to store a sequence of elements. Unlike arrays, linked lists consist of nodes where each node contains data and a pointer (or reference) to the next node in the sequence. This allows for efficient insertion and deletion of elements without the need to reorganize the entire structure.

https://media.geeksforgeeks.org/wp-content/uploads/20240826132228/singly-linked-list-in-c.webp

### How does a Linked List work?

- Each **node** contains two parts:
  1. **Data**: The value or information stored.
  2. **Next pointer**: A reference to the next node in the list.

- The first node is called the **head** of the list.
- The last node points to `NULL`, indicating the end of the list.
- Operations like traversal, insertion, and deletion involve moving through nodes via their `next` pointers.

---

## Experiments Overview

| File        | Description                                                                                         | Output                 |
|-------------|-------------------------------------------------------------------------------------------------|------------------------|
| `exp17a.cpp` | Creates a single node with a value (`1000`) and prints it. Demonstrates basic node creation and access. | `Node value: 1000`     |
| `exp17b.cpp` | Creates three nodes (`1000`, `2000`, `3000`), links them to form a singly linked list, and prints the list. | `1000 2000 3000`       |
| `exp17c.cpp` | Implements insertion at the head of the list with values `30`, `32`, and `35`, printing the list after each insertion. | `30-NULL` <br> `32-30-NULL` <br> `35-32-30-NULL` |

---
