# Software Development and Documentation Lab - Task 4

* **Name:** Waseem Gber
* **Student ID:** 202230017
* **Topic:** Writing Effective Conceptual, Procedural, and Reference Documentation

---

## Task 1: Conceptual Documentation

### Student Management System Overview
The **Student Management System (SMS)** is a lightweight software application engineered to assist educational institutions and administrative staff in managing student records efficiently. It serves as a centralized platform to handle student data securely and accurately.

### System Users
1. **Administrator:** Has full system privileges to add, view, and delete student records, as well as manage user access.
2. **Administrative Staff:** Uses the system daily to enter new admissions and retrieve student details.

### Purpose of the System
The primary purpose of the system is to automate and streamline the lifecycle of student data management. It reduces manual paperwork, eliminates human errors in record-keeping, and ensures that staff can instantly access, update, or remove student information when needed.

### Key Features Overview
* **Add Student:** Allows users to input new student credentials (Name, ID) into the database.
* **View Student List:** Displays a comprehensive tabular list of all currently enrolled students.
* **Delete Student:** Enables administrators to remove outdated or invalid student records using their unique ID.

---

## Task 2: Procedural Documentation
This section provides clear, step-by-step instructions for performing key operations within the system.

### Procedure 1: How to Add a Student
1. Open the **Student Management System** application on your device.
2. Navigate to the main dashboard and click on the **Add Student** button.
3. Enter the required student details in the designated input fields (e.g., *Full Name* and *Student ID*).
4. Review the entered data to ensure accuracy.
5. Click the **Save** button to store the record in the database.

### Procedure 2: How to Delete a Student
1. Open the application and access the **View Student List** section.
2. Locate the student you wish to remove by checking their unique ID or name.
3. Click on the **Delete** button next to the target student's entry.
4. Confirm the prompt message that appears on the screen (e.g., *"Are you sure you want to delete this student?"*).
5. The system will process the request and instantly update the student list.

---

## Task 3: Reference Documentation
This technical reference guide outlines the core functions, inputs, and descriptions for developers and advanced users.

| Function Name | Inputs / Parameters | Description |
| :--- | :--- | :--- |
| `addStudent()` | `name` (`String`), `id` (`int`) | Creates and inserts a new student record into the system database, validating against duplicate IDs. |
| `viewStudents()` | `None` | Retrieves and renders a complete list of all registered students in an organized format. |
| `deleteStudent()` | `id` (`int`) | Searches for a specific student record by their unique ID and permanently deletes it from the system. |

---

## Task 4: Compare Documentation Types
The following table provides a clear comparison highlighting five distinct differences between the three documentation types:

| Comparison Criteria | Conceptual Documentation | Procedural Documentation | Reference Documentation |
| :--- | :--- | :--- | :--- |
| **Core Focus** | Explains the **"why"** — high-level purpose and vision. | Explains the **"how"** — step-by-step execution. | Provides technical **"what"** — parameters, specs, and lookups. |
| **Primary Question** | What is this system and why does it exist? | How do I complete a specific task or process? | What are the exact functions, inputs, or properties? |
| **Target Audience** | Managers, stakeholders, and system architects. | End-users, beginners, and operations staff. | Software developers, engineers, and power users. |
| **Typical Structure** | Overviews, introductions, and conceptual guides. | Numbered sequential steps, tutorials, and walkthroughs. | Tables, lists of parameters, and API specifications. |
| **Representative Examples** | System overview, architecture description, and features. | Installation guide, setup steps, and user tutorials. | Function definitions, API endpoints, and class references. |

---

## Bonus Task: Markdown & GitHub README
This documentation has been successfully structured in standard Markdown syntax and is fully optimized to be uploaded as a `README.md` file in a GitHub repository.