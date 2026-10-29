# Class Test Marks Management System

## PROBLEM STATEMENT

In many colleges, class test marks are handled manually, which is time-consuming and less efficient. This project proposes the idea of a web application that digitally handles class test marks, which reduces paperwork, increases accuracy, and saves time. It will make the evaluation process easier for faculty members and other users like HODs, students, parents, and administrators. The application allows access based on the roles of the users through a secure login system.

## PROJECT OVERVIEW

This web application will allow faculty members to upload and edit marks, and the percentage and grade of the students will be calculated automatically. Different users will have different levels of access based on their roles.

## OBJECTIVES

- To automate the process of uploading and managing class test marks.
- To reduce paperwork and save time.
- To improve the accuracy of marks management.
- To allow parents and students to access the marks easily.
- To make the supervision of students' progress easier for HODs.

## USER ROLES AND PERMISSIONS

# Faculty

- Upload the marks.
- Edit the marks.
- View the marks of the students they teach.

# Students and Parents

- View the marks.
- Track academic progress.

# HODs

- View the marks of all the students in the department.
- Monitor students' reports and faculty submissions.

# Administrators

- Manage user accounts.
- Assign roles and permissions.

## INPUT FROM EACH USER 

| User | Input Provided | Purpose |
| --- | --- | --- |
| Student | Student ID, login credentials, basic profile details | Access personal marks and academic information |
| Parent | Parent ID, login credentials, student details | Monitor the student's marks and performance |
| Faculty | Faculty ID, subject, class, test details, student marks | Enter, update, and manage class test marks |
| HOD | HOD ID, login credentials, faculty, subject, and class information | Manage and monitor academic and marks-related information |


## APPLICATION FLOW

```
                         USERS
                           │
       ┌───────────┬───────┼───────┬───────────┐
       ▼           ▼       ▼       ▼
    Student     Parent   Faculty   HOD
       │           │       │       │
       └───────────┴───────┴───────┘
                           │
                           ▼
                     Login System
                           │
                           ▼
                  Role Authentication
                           │
                           ▼
                  Role-Based Dashboard
                           │
       ┌───────────┬───────┼───────┬───────────┐
       ▼           ▼       ▼       ▼
    View Marks  View Marks Enter/   Monitor &
                           Update    Performance
                            Marks
       │           │       │       │
       └───────────┴───────┴───────┘
                           │
                           ▼
                        Database
                           │
                           ▼
                   Marks & Reports
                           │
                           ▼
 ```                     Output

## UI FLOW

```                      Start
                           │
                           ▼
                       Login Page
                           │
                           ▼
                     User Dashboard
                           │
       ┌───────────┬───────┼───────┬───────────┐
       ▼           ▼       ▼       ▼
    Student     Parent   Faculty   HOD
    Dashboard  Dashboard Dashboard Dashboard
       │           │       │       │
       ▼           ▼       ▼       ▼
   View Marks  View Marks Manage   Monitor
                         Marks    Performance
       │           │       │       │
       └───────────┴───────┴───────┘
                           │
                           ▼
```                     Logout Page

## FEATURES

- Secure Login
- Upload and Update Marks
- Student Dashboard
- HOD Monitoring
- Digital Record Management
- Role-Based Access

## FUTURE SCOPE

- Attendance Management
- Performance Analysis
- Result Report Generation

## PROPOSED TECHNOLOGIES

- HTML
- CSS
- JavaScript
- MySQL

## CURRENT STATUS

The project is currently in the documentation and planning phase.
