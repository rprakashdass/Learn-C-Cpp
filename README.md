# Linked List Operations in C

This repository provides a basic implementation of linked list operations in the C programming language. It aims to help beginners understand the concepts and functions associated with linked lists.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Available Operations](#available-operations)
- [Contributing](#contributing)
- [License](#license)

## Introduction

A linked list is a data structure that consists of a sequence of nodes, where each node contains data and a reference (link) to the next node in the sequence. Linked lists are dynamic data structures that can grow or shrink during program execution.

## Prerequisites

To run the code provided in this repository, you'll need:

- A C compiler such as GCC or Clang
- Basic knowledge of the C programming language

## Installation

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/your-username/linked-list-operations.git
   ```

2. Change to the project directory:

   ```shell
   cd linked-list-operations
   ```

3. Compile the code using a C compiler:

   ```shell
   gcc linked_list.c -o linked_list
   ```

## Usage

To use the linked list operations, follow these steps:

1. Include the `linked_list.h` header file in your C program:

   ```c
   #include "linked_list.h"
   ```

2. Create a new linked list using the `createList()` function:

   ```c
   Node* myList = createList();
   ```

3. Perform various operations on the linked list using the available functions (see next section).

4. Free the memory allocated for the linked list when you're done:

   ```c
   freeList(myList);
   ```

## Available Operations

The following operations are provided by the linked list implementation in this repository:

- `createList()`: Creates an empty linked list and returns a pointer to the first node.
- `isEmpty()`: Checks if the linked list is empty.
- `getSize()`: Returns the number of elements in the linked list.
- `insertFront()`: Inserts a new element at the front of the linked list.
- `insertEnd()`: Inserts a new element at the end of the linked list.
- `insertAtPosition()`: Inserts a new element at a specified position in the linked list.
- `deleteFront()`: Deletes the first element from the linked list.
- `deleteEnd()`: Deletes the last element from the linked list.
- `deleteAtPosition()`: Deletes the element at a specified position in the linked list.
- `display()`: Displays the elements of the linked list.

Feel free to explore the source code for more details on the implementation of these functions.

## Contributing

Contributions to this repository are welcome. If you find any issues or want to add new features, please open an issue or submit a pull request.
