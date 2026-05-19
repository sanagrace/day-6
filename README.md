# day-6


# What is SOQL?
SOQL (Salesforce Object Query Language) is a query language in Salesforce used to retrieve data from Salesforce objects. It is similar to SQL but designed specifically for Salesforce data.

# What is an Apex Trigger?
An Apex Trigger is a piece of Apex code that runs automatically when records are created, updated, deleted, or restored in Salesforce. Triggers help automate actions based on data changes.

# Difference
Flow vs Trigger
    Flow	                                      Trigger
No coding required                       	Requires Apex coding
Easy to build                            	More advanced
Used for simple automation              	Used for complex logic
Drag-and-drop                             interface	Written in code
Limited flexibility	                      High flexibility

Before vs After Trigger
     Before Trigger	                                 After Trigger
Runs before record is saved	                  Runs after record is saved
Used to validate or modify data	              Used for actions after save
Faster processing	                            Can access saved record ID
Example: Update marks                       	Example: Send email notification


# Trigger Use Cases (5 Examples)
Automatically generate Student ID when a new student record is created.
Prevent saving marks greater than 100.
Send email notification when fees are paid.
Update attendance warning status automatically.
Create semester result records after exam marks are entered.


# Query Examples
Show all students from Computer Science department.
Find students with attendance below 75%.
Display all courses taught by a faculty member.
Show students whose fees are pending.
Find students who scored above 90 marks.


# Reflection: Why Enterprise Systems React Automatically to Data Changes
Enterprise systems handle large amounts of data every day, so automatic reactions are important for speed and accuracy. Features like Flows and Triggers help systems respond immediately when data changes happen. This reduces manual work, improves productivity, and ensures that business processes run smoothly and efficiently.
