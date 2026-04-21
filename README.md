# Singly Linked List Implementation in Java

A clean and modular implementation of a **Singly Linked List** (SLL) from scratch. This project is designed as part of a series on **Data Structures & Algorithms (DSA)**, focusing on efficient node management and Object-Oriented principles.

---

## 🚀 Standardized Features

Following **Software Engineering** best practices, the implementation uses consistent terminology:

* **`isEmpty()`**: Checks if the list has no nodes (Standardized from `empty`).
* **`size()`**: Returns the total number of elements in the list (Standardized from `countNodes`).
* **`display()`**: Prints all elements sequentially (Standardized from `displayList`).
* **Insertion Logic**:
    * `insertFirst(E data)`: Adds a node at the beginning.
    * `insertLast(E data)`: Appends a node to the end.
    * `insertAfterNode(E data, E target)`: Inserts data after a specific value.
* **Deletion Logic**:
    * `deleteFirst()` & `deleteLast()`: Removes nodes from either end.
    * `deleteNode(E data)`: Finds and removes a specific element.
* **Utility**: Includes `displayPreSussNode` to track the predecessor and successor of a node.

---

## 📊 Complexity Analysis

| Operation | Time Complexity | Space Complexity |
| :--- | :--- | :--- |
| **Insert (Head)** | $O(1)$ | $O(1)$ |
| **Insert (Tail)** | $O(n)$ (No Tail version) | $O(1)$ |
| **Delete (Head)** | $O(1)$ | $O(1)$ |
| **Search / Access** | $O(n)$ | $O(1)$ |

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
