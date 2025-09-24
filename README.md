# linked-lists-in-cpp-

## What is a Linked List?

A **linked list** is a fundamental data structure used to store a sequence of elements. Unlike arrays, linked lists consist of nodes where each node contains data and a pointer (or reference) to the next node in the sequence. This allows for efficient insertion and deletion of elements without the need to reorganize the entire structure.

<img width="801" height="230" alt="image" src="https://github.com/user-attachments/assets/114f4b01-7de1-4a16-84f3-9dd6706fe4cb" />

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
# Combined Algorithm for Linked List Experiments (Exp 17a, 17b, 17c)

This section outlines the combined algorithm used across all three experiments, demonstrating basic operations on singly linked lists including node creation, linking, and insertion at head.

---

## Combined Algorithm

1. **Define a Node Class**  
   - Create a class (`node` or `link`) to represent a linked list node.
   - Each node contains:
     - An integer data field.
     - A pointer to the next node (initially `NULL`).

2. **Experiment 17a – Create a Single Node**
   - Create a node with a specified value (e.g., `1000`).
   - Print the node's value.

3. **Experiment 17b – Create and Link Multiple Nodes**
   - Create three individual nodes with values (e.g., `1`, `2`, and `3`).
   - Link them sequentially:
     - Set the `next` pointer of the first node to the second.
     - Set the `next` pointer of the second node to the third.
     - The `next` pointer of the third node remains `NULL`.
   - Traverse from the first node (head) and print each node’s value until `NULL` is reached.

4. **Experiment 17c – Insert at Head and Display**
   - Initialize the `head` pointer as `NULL`.
   - Define a function `insert_head(head, data)`:
     - Create a new node with the given data.
     - Set the new node’s `next` to the current `head`.
     - Update `head` to point to the new node.
   - Define a function `disp(head)` to:
     - Traverse the list from `head`.
     - Print each node's data followed by a separator (e.g., `-`).
     - Print `"NULL"` at the end of the list.
   - Perform multiple insertions at the head (e.g., `30`, `32`, `35`) and display the list after each insertion.

---

This combined algorithm illustrates key concepts in singly linked list operations:
- Node creation
- Node linking
- Insertion at the head
- List traversal and display
