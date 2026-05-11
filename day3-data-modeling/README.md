1. Difference between App, Object, Record and Field
 App : A collection of related tools and objects
ex: College Management
Object: A database table that stores data
ex: student Object
Record: A single row of data inside an object
ex: Student: Harika
Field: A column that stores specific information
ex: Student Name, Age

2. Standard vs Custom Objects
Standard Objects
Already provided by Salesforce
Used for common business needs
Examples: Account, Contact
Standard objects are prebuilt in Salesforce for common CRM operations.
Custom Objects
Created by users
Used for specific business requirements
Examples: Student, Course
Custom objects are created according to business needs like College Management Systems.

3. College Management System Data Model
Objects
Student
Faculty
Course
Department
Relationships
Department → Faculty
One department can have many faculty members.
Lookup Relationship
Department → Course
One department can offer many courses.
Lookup Relationship
Course → Student
One course can have many students.
Lookup Relationship
Faculty → Course
One faculty member can teach many courses.
Lookup Relationship
Simple Data Model Diagram
Plain text
Department
   |
   |---- Faculty
   |
   |---- Course
               |
               |---- Student
   
4. Formula Fields

1. Full Name
Formula
Plain text
First Name + Last Name
Why automatic?
It reduces manual work and avoids typing mistakes.
2. Percentage
Formula
Plain text
(Obtained Marks / Total Marks) * 100
Why automatic?
The system calculates marks instantly and accurately.
3. Remaining Seats
Formula
Plain text
Total Seats - Enrolled Students
Why automatic?
It helps management know seat availability in real time.

5. Validation Rules
1. Email Cannot Be Empty
Rule
Student email must be entered.
Problem Prevented
Avoids missing communication details.
2. Student Age Cannot Be Negative
Rule
Age must be greater than 0.
Problem Prevented
Stops invalid student data.
3. Course Seats Cannot Exceed Limit
Rule
Enrolled students should not exceed total seats.
Problem Prevented
Prevents overbooking of courses.

6. Reflection 
Companies need structured data because it keeps information organized, accurate, and easy to manage.
 Random spreadsheets create duplicate data, errors, and confusion. Structured systems like Salesforce help businesses track relationships,
automate processes, and make better decisions quickly.

Screenshots
