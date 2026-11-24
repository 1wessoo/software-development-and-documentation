# Software Development and Documentation Lab - Task 1

* **Name:** Waseem Gber
* **Student ID:** 202230017

---

## Student Grade Calculator

### Introduction
The student grade calculator is a software program designed to calculate students' grades based on their marks in different subjects or assessments. It simplifies the grading process by automatically calculating the total score, average percentage, and final letter grade, helping students and teachers evaluate academic performance accurately and efficiently.

### Objectives
The main objectives of the program are to:
* Calculate students' total marks.
* Determine the average percentage.
* Assign a letter grade based on the student's performance.
* Display the final results clearly.
* Reduce manual calculation errors and save time.

### Scope
The program can be used by students, teachers, and educational institutions to calculate and review academic results. It is suitable for basic grading tasks and can be expanded to support multiple students, subjects, and grading systems.

---

### System Requirements

#### Hardware Requirements
* Computer or laptop
* Keyboard and display
* Minimum 2 GB RAM

#### Software Requirements
* An operating system such as Windows, macOS, or Linux
* A programming language such as Python, Java, or C++
* A suitable code editor or IDE (if required)

---

### Program Features
The student grade calculator includes the following features:
* **Input marks:** Allows the user to enter marks for different subjects.
* **Calculate total:** Adds all entered marks.
* **Calculate average:** Computes the average percentage.
* **Determine grade:** Assigns a letter grade according to predefined grading criteria.
* **Display results:** Shows the total marks, average, and final grade.
* **Input validation:** Checks that marks are within the permitted range.

### How the Program Works
The program follows these steps:
1. Start the program.
2. Ask the user to enter the student's marks.
3. Validate the entered values.
4. Calculate the total marks.
5. Calculate the average percentage.
6. Determine the appropriate letter grade.
7. Display the results.
8. End the program.

---

### Grading System
The following example grading scale can be used:

| Percentage | Letter Grade |
| :--- | :---: |
| 90–100% | A |
| 80–89% | B |
| 70–79% | C |
| 60–69% | D |
| Below 60% | F |

### Calculation Method
* **Total Marks:**
  $$\text{Total marks} = \text{sum of all subject marks}$$

* **Average Percentage:**
  $$\text{Average percentage} = \left( \frac{\text{total marks obtained}}{\text{maximum possible marks}} \right) \times 100$$

* **Final Grade:**
  The program compares the calculated percentage with the grading scale and assigns the corresponding letter grade.

---

### Example Output

**Suppose a student receives the following marks:**
* **Mathematics:** 85/100
* **English:** 90/100
* **Science:** 75/100
* **Computer Science:** 80/100

**Results:**
* **Total marks:** 330/400
* **Average percentage:** 82.5%
* **Final grade:** B

---

### Input Validation and Error Handling
The program should:
* Reject negative marks.
* Reject marks greater than the maximum allowed score.
* Require valid numeric input.
* Prevent calculations when required marks are missing.
* Display an appropriate error message when invalid input is entered.

### Limitations
* The grading scale may need to be configured for different institutions.
* Basic versions may support only one student at a time.
* The program may not store results permanently unless a database or file system is added.
* Weighted assignments and special grading rules may not be supported in the initial version.

---

### Future Improvements
Possible improvements include:
* Adding student names and identification numbers.
* Supporting multiple students and subjects.
* Saving results to a file or database.
* Adding a graphical user interface (GUI).
* Generating printable grade reports.
* Supporting weighted assessments and customizable grading scales.

### Maintenance
The program should be tested regularly to ensure accurate calculations. Developers should update the grading scale when requirements change, correct reported errors, and verify that invalid inputs are handled properly.

### Conclusion
The student grade calculator provides a simple and efficient way to calculate students' academic performance by automating total-mark and percentage calculations and assigning letter grades. The program reduces manual effort and improves accuracy, and its modular design also allows additional features to be introduced in the future.