📚 Library Management System

A simple yet powerful Library Management System built using Java (JDBC) and MySQL, designed to automate book management, member registration, book issuing, returning, and fine calculation. This project reflects core backend programming skills with clean database integration and real-world logic.

⭐ Key Features
1. Add or Update Book

Allows adding new books into the library database.

Supports updating details of an existing book (title, author, quantity, etc.).

Prevents duplication by checking existing book IDs.

2. Register Member

Stores member details in the database using MySQL.

Ensures unique member IDs and maintains accurate user records.

Enables members to borrow, return, and access library services.

3. List Available Books

Displays all books with ID, title, author, genre, and availability.

Filters only books with quantity > 0.

Helps students quickly identify what is available.

4. Search Book by Title

Efficient search using SQL LIKE queries.

Helps locate books even if only part of the title is known.

Ensures smooth browsing for large datasets.

5. Issue Book

Issues a book to a registered member.

Automatically reduces available stock.

Stores issue date in the database.

Prevents issuing if the book is out of stock.

6. Return Book

On returning, stock quantity is updated.

Return date is stored in the database.

Triggers fine calculation if the book is overdue.

7. Fine Calculation (Automated)

Fine is auto-calculated based on the number of extra days after the allowed period.

Default assumption:

15 days = No fine

After that = Fine applied per day (as defined in DB logic)

Helps maintain proper discipline in book usage.

8. Exit

Cleanly exits the application.

Ensures no pending DB connections remain open.

🎯 Why This Project Is Unique

The system uses fully functional JDBC–MySQL integration, not dummy data.

All operations — issuing, returning, fines, registration — are live database transactions.

The project applies real-world constraints such as stock limits, overdue fines, and valid member checks.

It mirrors the working style of actual small-scale library systems used in colleges and institutions.

The logic is clean, modular, and easy to extend for future features like dashboards, GUI, or web integration.

🌍 Real-World Relevance

Libraries still rely heavily on structured, error-free backend systems.
Your project solves real problems:

Prevents book loss

Maintains accurate member data

Tracks late returns responsibly

Reduces manual paperwork

Offers a dependable solution for schools, colleges, and community libraries

This makes the system practically usable and professionally scalable.
