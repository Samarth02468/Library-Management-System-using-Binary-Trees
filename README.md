# Library Management System: Searching Catalogues Using Binary Search Tree
Objective
The main objective of this project is to develop a Library Management System that allows students to issue books while enabling the admin (librarian) to manage the library records efficiently. The system is divided into two main perspectives:

Student's Perspective – Issuing and returning books.
Admin's Perspective – Adding, updating, and deleting book records.

Admin's Role

Login System:

The admin must log in using a predefined username and password to access the system.
Managing Books:

The admin can add, delete, and update book records.
When a book is added, it is stored in a Binary Search Tree (BST), ensuring the books are sorted for efficient searching.
If a book is deleted, it will be removed from the BST.
Updating Books:

The admin can modify the quantity of books.
The name of a book can also be updated.
Student's Role
Login System:

Students must log in using their valid university ID to issue or return books.
A student can only proceed if their ID matches the university's registered student list.
Issuing Books:

The student enters the book name, which is searched within the BST.
If the book is not found, the system displays:
"Book is not available in the library."
If the book is out of stock, the system displays:
"This book is currently unavailable. Please try after some days."
A student cannot issue more than 2 books at a time.
Returning Books & Fines:

The issuing date and time of a book are recorded by the librarian.
If the student fails to return the book by the due date, a fine will be imposed.
Binary Search Tree (BST) Implementation
The system utilizes a Binary Search Tree (BST) to store and search book records efficiently.
Advantages of BST in the system:
Books are automatically sorted in the tree.
Searching for a book by name is fast and efficient.

