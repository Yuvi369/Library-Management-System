# Library-Management-System
Build a Data Model for a Library Management using salesforce.com



Library Management System:

Description: Develop an app to manage book loans, track due dates, and manage library inventory.

Skills: 
1.Salesforce objects
2.Fields
3.Configuration Management
4.Process Improvement and Optimization
5.System Design and Implementation
6.Data Science

OverView :
          This Library Management System is built using Salesforce to efficiently manage library operations. The system leverages Salesforce’s robust platform to handle various aspects of library management, including tracking books, borrowers, and loans. Additionally, it includes comprehensive reports and dashboards to provide insights into library activities.

Key-Features :

1.Objects :

  Object: Book__c
  Fields: Action, Available Quantity, Book Code, Book Name, Book Price, Year of Release
  Functionality: This object stores all the information related to the books available in the library. It tracks the availability status of each book to ensure efficient management of the library’s         
  inventory.


  Object: Borrower__c
  Fields: Borrowers Name, Email, Number of Borrowers, Gender, Designation
  Functionality: This object keeps track of all the library members. It stores their personal information and membership details, allowing the library to manage memberships effectively.


  Object: Loan__c
  Fields: Book, Borrower, Loan Date, Due Date, Return Date, Fine Amount
  Functionality: This object records the details of each loan transaction. It links books and borrowers, tracks loan and return dates, and calculates fines for overdue books.

2.Reports and Dashboards
  New Borrower History Report: Borrower history .
  New Loans With Borrower Report: Visual representation of the availability status of borrowers.
  New Books Report: Report of Books
  New Loans With Books Report : Loans related to Books
        
