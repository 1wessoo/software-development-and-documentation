# Lab Task: Refactoring a Messy Document

* **Course:** Software Documentation and Development Lab
* **Student Name:** Waseem Gber
* **Student ID:** 202220468

---

## Task 1: Identify Problems

After analyzing the original document, the following problems were identified:

1. **Missing Headings:** The document does not contain clear headings to organize the information.
2. **Poor Grammar:** Several sentences contain grammatical mistakes.
3. **Incorrect Capitalization:** Sentences and important terms are not consistently capitalized.
4. **Informal Vocabulary:** Words such as (`stuff`), (`like`), and (`click around`) are unsuitable for professional documentation.
5. **Unclear Instructions:** The document does not explain how users should perform the available operations.
6. **Ambiguous Information:** Expressions such as (`choose ID`) or (`something`) make the instructions confusing.
7. **Lack of Organization:** Information is presented without a logical order.
8. **Missing Feature Explanations:** The system features are mentioned without describing their purposes.
9. **Unclear Data Management:** The document does not explain how student information is stored or managed.
10. **Missing Technical Details:** There is no organized explanation of system functions, their inputs, or their expected behavior.

---

## Task 2: Conceptual Documentation
### Student Management System (SMS)

#### 1. Introduction
The Student Management System (SMS) is a software application developed to help educational institutions organize student information. It provides basic operations that allow users to add new students, view existing student records, and delete unwanted records. The application aims to simplify student information management and provide an organized way to access student records.

#### 2. System Purpose
The main purpose of the Student Management System is to make student record management easier and more efficient.

The system provides the following capabilities:
* Creating new student records
* Displaying registered students
* Removing existing student records
* Organizing student information
* Providing a simple interface for managing student records

#### 3. Main System Features

| Feature | Description |
| :--- | :--- |
| **Student Registration** | Users can add a new student by entering the required information, including the student's name and ID. |
| **Student Viewing** | Users can display the available student records in a list to review student information. |
| **Student Deletion** | Users can select an existing student record and remove it from the system using the student's ID. |
| **Student Information Management** | The system provides a simple interface for performing basic operations on student records. |

#### 4. Target Users
The system is intended for the following users:
* **Teachers:** Access student information when needed.
* **School Administrators:** Manage student records and maintain organized information.
* **Administrative Staff:** Enter student information and review existing records.

#### 5. General System Description
The Student Management System uses a graphical user interface that allows users to interact with its available features. The main interface provides options for adding, viewing, and deleting student records.

> **Note:** The exact method of data storage depends on the application's implementation and should be verified before documenting it as a confirmed feature.

---

## Task 3: Procedural Documentation
### Student Management System - Operating Instructions

This section explains how users can perform the main operations of the Student Management System.

#### 1. Starting the Application
* Locate the Student Management System application.
* Open the application.
* Wait until the main interface appears.
* Identify the available operations.

#### 2. Adding a New Student
To add a student record, follow these steps:
* Open the application.
* Select the **Add Student** option.
* Enter the student's name in the **Student Name** field.
* Enter the student's ID in the **Student ID** field.
* Review the entered information.
* Click the **Save** button.
* Check the student list to verify that the record has been added.

| Status | Details |
| :--- | :--- |
| **Expected Result** | The system should display the newly added student if the operation is successful. |
| **If an error occurs** | Check that all required fields are completed and that the student ID is valid. Then try again. |

#### 3. Viewing Student Records
To view the registered students, follow these steps:
* Open the application.
* Select the **View Students** option.
* Wait for the records to appear.
* Review the displayed student information.
* Search for a specific student if a search feature is available.

| Status | Details |
| :--- | :--- |
| **Expected Result** | The system displays the available student records. |

#### 4. Deleting a Student
To remove a student record, follow these steps:
* Open the application.
* Navigate to the student list.
* Identify the student you want to remove.
* Enter or select the student's ID.
* Click the **Delete** button.
* Confirm the deletion if the system requests confirmation.
* Check the student list to make sure the record has been removed.

| Status | Details |
| :--- | :--- |
| **Expected Result** | The selected student record is removed from the displayed records. |
| **Important Note** | Always verify the student's ID before deleting a record because the deletion may be permanent. |

#### 5. Troubleshooting

| Problem | Suggested Solution |
| :--- | :--- |
| **Application does not start** | Close and reopen the application. |
| **Student information is not accepted** | Check the entered information and required fields. |
| **Student cannot be deleted** | Verify that the student ID is correct. |
| **Student records are not displayed** | Check whether student records are available. |
| **Student information is not saved** | Check the application's configured storage system. |

---

## Task 4: Reference Documentation
### Student Management System – Function Reference

This section provides a reference for the main operations of the Student Management System.

#### 1. Functions Table

| Function | Input | Description |
| :--- | :--- | :--- |
| `openApp()` | None | Opens the application and displays the main interface. |
| `addStudent()` | Student Name, Student ID | Creates a new student record. |
| `viewStudents()` | None | Displays the available student records. |
| `deleteStudent()` | Student ID | Removes a student record using the provided ID. |

#### 2. Input Information

| Input Name | Data Type | Description |
| :--- | :--- | :--- |
| **Student Name** | String | Represents the student's full name. |
| **Student ID** | Integer or String | Represents the unique identification number of the student. |

#### 3. Function Explanation

| Function | Expected Result |
| :--- | :--- |
| `openApp()` | The application main screen appears. |
| `addStudent()` | A new student record appears in the system. |
| `viewStudents()` | A list of student information is displayed. |
| `deleteStudent()` | The selected record is removed from the student list. |

> **Note:** The function names above are descriptive names used for documentation. They do not necessarily represent the actual names of functions in the source code.

---

## Task 5: Before vs. After Comparison

The following table explains the main improvements made during the documentation refactoring process.

| Aspect | Original Document (Before) | Improved Document (After) | Improvement |
| :--- | :--- | :--- | :--- |
| **Organization** | Information was written in one paragraph | Information is divided into organized sections | Makes information easier to find |
| **Grammar** | Contains grammatical and punctuation mistakes | Uses correct grammar and punctuation | Improves readability |
| **Language** | Uses informal expressions | Uses professional technical language | Makes the document more professional |
| **Instructions** | Provides unclear instructions | Includes numbered steps for each operation | Helps users understand how to use the system |
| **Features** | Mentions features without explanation | Explains each main feature separately | Improves understanding of the system |
| **Technical Details** | Does not explain function inputs | Includes a reference table with functions and inputs | Provides organized technical information |
| **Formatting** | Uses inconsistent formatting | Uses headings, lists, and tables | Improves document presentation |
| **Error Handling** | Does not explain how to handle errors | Includes basic troubleshooting instructions | Helps users deal with common problems |

---

## Bonus Task: GitHub
*(Add your GitHub repository link or details here)*