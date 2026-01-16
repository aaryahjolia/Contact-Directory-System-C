# Contact Directory System

A comprehensive Contact Management Application built in C, designed to efficiently manage contacts using advanced data structures. Use this application to store, organize, and retrieve contact information directly from your terminal.

## Overview

This project mimics the functionality of a standard phonebook application found on mobile devices. It is built from the ground up to demonstrate efficient memory management and data organization using a **Circular Doubly Linked List**. This choice of data structure allows for bidirectional traversal and efficient insertion/deletion operations, making the user experience smooth and responsive.

## Key Features

- **Add Contacts**: Save names and 10-digit phone numbers.
- **Organization**: Automatically sorts contacts alphabetically by name as you add them.
- **Search**: Find contacts quickly by name or even a partial substring (e.g., searching "John" finds "John Doe").
- **Update Details**: Modify existing names, numbers, or toggle favorite status.
- **Favorites List**: Quickly access your most important contacts.
- **Delete**: Remove contacts you no longer need.
- **Smart Formatting**: Names are automatically capitalized for a clean display.

## Technical Implementation

- **Language**: C
- **Data Structure**: Circular Doubly Linked List
- **Algorithms**: Custom sorting for alphabetical order, substring search for queries.

## Getting Started

### Prerequisites
You need a C compiler (like GCC) installed on your system.

### Compilation
Open your terminal and navigate to the project directory. Compile the source code using the following command:

```bash
gcc Contact_Directory_System.c -o contact_app
```

### Running the Application
Once compiled, you can launch the application with:

```bash
./contact_app
```

## Usage Guide
Upon launching, you will be presented with an interactive menu:

1.  **Add Contact**: Follow the prompts to enter details.
2.  **Remove Contact**: Delete entries by name.
3.  **Show Contacts**: View your entire directory.
4.  **Search Contacts**: Look up specific people.
5.  **Update Details**: Edit information for existing contacts.
6.  **Show Favourite List**: View your pinned contacts.
7.  **Exit**: Close the application.

---
**Author**: Aarya Ahjolia
