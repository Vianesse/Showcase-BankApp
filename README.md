# Showcase-BankApp
Project-Showcase
USF Coding Bootcamp Certificate - Two Projects Showcase

Project 1 - Banking Application Description Leveraging Java 8, create an application that simulates simple banking transactions.

Requirements

-Build the application using Java 8 -All interaction with the user should be done through the console using the Scanner class -Users should be able to open an account -Once the account is open, customers should be able to withdraw, deposit, and transfer funds between accounts -All basic validation should be done, such as trying to input negative amounts, overdrawing from accounts etc. -Logging should be accomplished using Log4J -All transactions should be logged -Create an SQL script that will create a user in an SQL database and a table schema for storing your bank users and account information. -Have your bank application connect to your SQL database using JDBC and store all information that way. -You should use the DAO design pattern for data connectivity.

Evaluation -The project will be evaluated between two main catagories: core functionality and design of your project and presentation of project during the project showcase and implemented stretch goals. Evaluation results will shared with each project team after the project showcase and a code review. The evaluation will be further subdivided as follows:

-Ability to persist meaningful data in the database, retrieve it, and display it to the console. -Ability to make withdrawals from, deposits to, and transfers between accounts. -Proper database schema achieving 3rd normal form. (E.g. Accounts have a proper relationship to their owning user.) -Proper use of DAO design pattern. -Reasonable test coverage of the service layer and proper logging. -Appropriate validation for user inputs. -Create different user types with different permissions: -Customers with base functionality to apply for new accounts, update their own records, and accounts. -Bank Employee with the ability to view all customer information including account information, account balances, and personal information. Additionally they should be able to approve/deny customer applications to open an account. -Bank admins who can edit all accounts including approving/denying accounts, withdrawing, depositing, transferring from all accounts, and canceling accounts. -Login, register, update and logout functionality for all users. -Customers of the bank should be able to register and then sign in with a username and password. -Customers should be able to apply for joint accounts. -Include one stored procedure in your database.

Employee Reimbursment System (ERS) Executive Summary The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. [Stretch Goal] Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.

Reimbursement Types Employees must select the type of reimbursement as: LODGING, TRAVEL, FOOD, or OTHER.

State-chart Diagram (Reimbursement Statuses) -see attached

Logical Model -see attached

Physical Model -see attached

Use Case Diagram -see attached

Activity Diagram -see attached

Technical Requirements The back-end system shall use JDBC to connect to a PostgreSQL database. The application shall deploy onto a Tomcat Server. The middle tier shall use Servlet technology for dynamic Web application development. The front-end view shall use HTML/CSS/JavaScript to make a single-page application that can call server-side components. The middle tier shall follow proper layered architecture, have reasonable (~70%) test coverage of the service layer, and conform to general REST standards up to at least level 2 of the Richardson Maturity Model. (NOTE: All diagrams above show models with all stretch goals implemented. They may be adjusted as necessary. Datatypes shown are OracleSQL based and will need to be converted to PostgreSQL.)

Stretch Goals:

Include timestamps for when reimbursements are submitted and approved. Use a trigger in the database. Encrypt Passwords in the backend/database. Implement finance managers to approve requests. Ensure finance managers can not approve their own requests. Use bootstrap for styling.
