1. ABOUT

Name: Galaxy Library System
Version: 1.0
Date of creation: 29 September 2018

Contributors: 
- Geraldine Tay Hui Ling
- Ng Yan Bo
- Shalin Christina Stephen Selvaraja
- Tran Thi Ngoc Thuy
- Zhao Pengkai

-----------------------------------------------------------------------------------------
2. SOFTWARE REQUIREMENTS

Visual Studio 2017 or later versions of Visual Studio
SQL server with a connection to the Galaxy database. A sample database, Galaxy.bak, is enclosed within the package.

-----------------------------------------------------------------------------------------
3. ADMIN RIGHTS

The following admin user account can create, modify and delete staff information, thereby controlling the access rights to the system. This is in addition to the functions accessible to library staff users.
 
User: Venkat
Pass: P@ssword1

-----------------------------------------------------------------------------------------
4. USERS

Library staff would be able to log in with their username and password, accessing most of the functions of the Galaxy Library system, including search, create, modify, borrow, return, and report generation. The following is a sample user account.

User: Blake
Pass: BlakeS01

Library members are able to access the book search function without logging into the system. This system can be accessed by the computers in the library.

-----------------------------------------------------------------------------------------
5. SPECIAL FEATURES

- Display or hide system functions based on user types (admin vs staff)
- User-friendly Search screens with tabbing and confirming selected rows using the return key (Enter). (abstract class with inheritance)
- Password reset by email address validation – Users would input their new password twice and receive a prompt if they do not match
- Users have an option to show or display password when typing it
- Auto-generated ID for new book, member and transaction records
- Pre-defined borrowing limit of 3 and loan extension limit of 3 times
- When borrowing a book, the loan period is auto-calculated and differentiated based on member categories (student and lecturer). - Lecturers have a 20-day loan period while students have a 10-day loan period.
- View borrowing history concurrently while viewing details of a book or member
- During book return, the return date is auto-populated as today’s date. The fine amount is auto-calculated if the return date is later than the due date. The fine amount can be cleared with the Pay function. Previous book loans that are not returned are displayed.
- During book return, user have an option to add the book price to the fine amount, should it be deemed damaged.

-----------------------------------------------------------------------------------------
6. OTHER SYSTEM FEATURES

The following are features of the Galaxy Library system:

- Password-protected system, accessible by username and password in the database
- Search for books information without logging in
- Search for Member Details with filters on member ID, name, phone number and email address.
- Search for Book Details with filters on the book ID, book title, book category, publisher, author, total stock, number of books borrowed, price of book and availability
- Auto-population of fields when a book or member record is selected from the search display
- Message prompts for invalid data, empty fields or successful updates
- Members and books that are no longer relevant can have its status changed to closed and unavailable respectively, so that a history can be retained. The record would not be deleted to preserve referential integrity to the Transaction records.
- Generate reports including a book list, manage report, and book receipt
- Tooltips
- Inheritance, Abstract, Interface, Exceptions(try catch)
Status bar indicates record index while navigating between customer and book records
