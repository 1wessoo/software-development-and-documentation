# Software Development and Documentation Lab - Task 2

* **Name:** Waseem Gber
* **Student ID:** 202230017

## Function Documentation - `calculate_grade`
 (`calculate_grade`):

```python
def calculate_grade(score):
    # Determine the student's grade based on their numerical score
    # Use a simple grading scale to provide consistent and fair evaluation
    if score >= 90:
        return "A"
    elif score >= 80:
        return "B"
    elif score >= 70:
        return "C"
    elif score >= 60:
        return "D"
    else:
        return "F"
```