# Task Manager

## Description
Task Manager is a web application that helps you manage and organize your tasks. It allows you to add new tasks, mark them as completed, and delete them when they are no longer needed. You can also categorize your tasks for better organization.

## Features
- Add new tasks with descriptions, due dates, and categories.
- Mark tasks as completed by checking checkboxes.
- Delete tasks individually or in bulk.
- Organize tasks by categories.
- Responsive design for desktop and mobile devices.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS (Embedded JavaScript) for templates
- Bootstrap for styling

### Usage
Add new tasks with descriptions, due dates, and categories using the "Add Task" form.
Mark tasks as completed by checking the checkboxes.
Delete tasks individually by clicking the "Delete" button next to each task or delete multiple tasks at once.
Organize tasks by selecting different categories from the dropdown menu.
View your tasks in a clean and organized list.


# [Author]
-Name : Hemendra

-LinkedIn : https://www.linkedin.com/in/hemendra-dcvs/

-Github : https://github.com/Hemendra-DCVS

-Email : hemendrachanti@gmail.com








+------------------------+        +----------------------+
|       Patient          |        |        Doctor        |
|------------------------|        |----------------------|
| Aadhaar No. (PK)       | 1---M  | Doctor ID (PK)       |
| First Name             |        | First Name           |
| Last Name              |        | Last Name            |
| DOB                    |        | Years of Experience  |
| Contact Number         |        | Type (e.g., Cardiologist)|
| Gender                 |        | Contact Number       |
      
         |                            |
         |                            |
         |                            |
         |                            |
         M                            M
+------------------------+        +----------------------+
|     Appointment        |        |  Prescription Slip   |
|------------------------|        |----------------------|
| Appointment ID (PK)    | 1---M  | Slip Number (PK)     |
| Patient Aadhaar No.    |        | Prescription Date    |
| Doctor ID (FK)         |        | Doctor ID (FK)       |
| Appointment Date       |        | Patient Aadhaar No. (FK) |
   
         |
         |
         |
         |
         M
+------------------------+
|       Medicine         |
|------------------------|
| Medicine ID (PK)      |
| Type                  |
| Price                 |
| Quantity              |
| Expiration Date       |

