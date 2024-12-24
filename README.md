**harini G** **Company**: CODETECH IT SOLUTIONS
**Id**: CT08DS78 **Domain**: PYTHON PROGRAMMING
**Duration**: NOV-30 TO DEC-30,2024.
---

# Student Grade Tracker

A simple Python-based Student Grade Tracker that allows users to manage student records, add grades, calculate averages, and display student information. This tool is perfect for educators, tutors, or anyone needing to track academic performance over time.

## Features

- **Add New Student**: Users can add new students to the system.
- **Add Grades**: Users can input grades for a student and track their performance.
- **Calculate Average Grade**: Automatically computes the average grade for each student.
- **Display Student Info**: View detailed information about a student, including their grades and average.
- **Interactive Menu**: A command-line menu to navigate through the options and manage student data.

## Requirements

- Python 3.x or later.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/student-grade-tracker.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd student-grade-tracker
   ```

3. **Run the script**:

   Ensure you have Python 3.x installed, then execute the following:

   ```bash
   python grade_tracker.py
   ```

## How It Works

The program will present an interactive menu with the following options:

1. **Add New Student**: Enter the student's name, and a new student record is created.
2. **Add Grades for a Student**: Choose an existing student and input their grades. You can keep adding grades until you type a non-numeric value (e.g., 'done').
3. **Display Student Info**: View the student's grades and their average grade.
4. **Exit**: Exit the program.

### Example Usage

```text
Student Grade Tracker
1. Add New Student
2. Add Grades for a Student
3. Display Student Info
4. Exit
Enter your choice: 1
Enter student's name: John Doe
Student John Doe added successfully!

Student Grade Tracker
1. Add New Student
2. Add Grades for a Student
3. Display Student Info
4. Exit
Enter your choice: 2
Enter student's name: John Doe
Enter grade for John Doe (or type 'done' to stop): 85
Enter grade for John Doe (or type 'done' to stop): 90
Enter grade for John Doe (or type 'done' to stop): done

Student Grade Tracker
1. Add New Student
2. Add Grades for a Student
3. Display Student Info
4. Exit
Enter your choice: 3
Enter student's name to view info: John Doe
Student: John Doe
Grades: [85.0, 90.0]
Average Grade: 87.50
```

## Error Handling

- **Non-numeric Input**: If a user enters a non-numeric value when adding a grade, the program stops accepting grades and moves on.
- **Student Not Found**: If a user attempts to add grades or view info for a non-existent student, the program will inform them that no student with the given name exists.
  
## Contributing

Contributions are welcome! If you'd like to contribute to the project, you can fork the repository, make your changes, and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Notes:

- Replace `yourusername` with your actual GitHub username.
- If you'd like to add more details, such as screenshots or specific installation instructions, feel free to enhance this template


## SCREEN SHOT
![Screenshot 2024-12-24 110147](https://github.com/user-attachments/assets/c0c36a73-9658-4d7b-9ac3-c20c6d405c79)

