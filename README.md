# Library-management-system-using-c-
This is a Library Management System implemented in C. It provides various functionalities for managing books and members in a library, including adding, searching, issuing, and returning books. The system interacts with files (librecord.txt and membrrecord.txt) to store and retrieve information.

Key Features:
Add a New Book (Addbook()):

Prompts the user for book details (ID, name, author, number of titles).

Stores book information in librecord.txt.

Search for a Book (Searchbook()):

Searches for a book by name.

Displays book details if found.

Display Complete Information (Displaybook()):

Prints all books and member records stored in files.

List All Books by an Author (Author()):

Searches for books by a specific author.

List Titles of a Book (Titlelist()):

Displays the titles associated with a book.

Show Book Stock & Issued Books Count (Stock()):

Displays the count of issued books and books in stock.

Issue a Book (Issue()):

Checks if a member has available library cards.

Changes the status of the book if issued.

Return a Book (bookret()) (Not implemented in the provided code).

Add a New Member (Addmembr()):

Adds a new library member with details like ID, name, department, and phone number.

Exit the Program (Exit()).

How it Works:
Uses file handling to store and retrieve book and member data.

The menu-driven approach allows users to select options (1-10).

Book status is tracked using an IN (available) and OUT (issued) system.

Member details include available library cards to control book borrowing.










