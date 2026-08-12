# Student Practice Tracker

A simple Java console application that helps students track their daily Java practice progress.

## Project Overview

**Project Title:** Student Practice Tracker  
**Project Goal:** Build a beginner-friendly Java console application for tracking daily Java practice including student details, completed topics, and solved questions.

## Concepts Used

- Classes and Objects
- Instance Variables
- Local Variables
- Methods and Method Parameters
- `this` Keyword
- Scanner for User Input
- if-else Statements
- while Loops
- Basic Arithmetic Operators

## Project Structure

```
├── src/
│   ├── Student.java      # Student class with instance variables and methods
│   └── StudentApp.java   # Main application class with menu-driven interface
├── output/
│   └── output.txt        # Sample execution output
└── README.md             # This file
```

## Classes

### Student.java
Contains the following instance variables:
- `name` (String) - Student's name
- `courseName` (String) - Course name
- `completedTopics` (int) - Number of completed topics
- `questionsSolved` (int) - Number of solved questions

**Methods:**
- `setDetails(String name, String courseName)` - Sets student name and course
- `setProgress(int completedTopics, int questionsSolved)` - Sets initial progress values
- `displayDetails()` - Displays student name and course
- `displayProgress()` - Displays completed topics and questions solved
- `addTopics(int newTopics)` - Adds new completed topics to existing count
- `addQuestions(int newQuestions)` - Adds new solved questions to existing count

### StudentApp.java
Main application class containing the `main()` method with:
- Scanner for user input
- Menu-driven interface
- While loop for continuous operation until exit
- Switch-case for menu option handling

## How to Compile and Run

### Prerequisites
- Java Development Kit (JDK) installed
- Java added to system PATH

### Steps

1. **Navigate to the project directory:**
   ```bash
   cd e:\KodNest\Fourth-PRD-Implementation
   ```

2. **Compile the Java files:**
   ```bash
   javac src\Student.java src\StudentApp.java
   ```

3. **Run the application:**
   ```bash
   java -cp src StudentApp
   ```

## Sample Execution

The application will prompt for:
1. Student Name
2. Course Name
3. Completed Topics
4. Questions Solved

Then displays a menu with options:
1. View Student Details
2. View Progress
3. Add Completed Topics
4. Add Solved Questions
5. Exit

See `output/output.txt` for a complete sample execution.

## Features

- ✅ Enter and store student details (name, course)
- ✅ Track completed topics and solved questions
- ✅ View current student details
- ✅ View current progress
- ✅ Add new completed topics (adds to existing count)
- ✅ Add new solved questions (adds to existing count)
- ✅ Menu-driven interface with continuous loop
- ✅ Input validation for menu choices
- ✅ Clean exit with thank you message

## Requirements Fulfilled

All 17 steps from the project requirements have been implemented:
1. ✅ Student class with instance variables
2. ✅ setDetails() method with this keyword
3. ✅ setProgress() method with this keyword
4. ✅ displayDetails() method
5. ✅ displayProgress() method
6. ✅ addTopics() method (adds to previous value)
7. ✅ addQuestions() method (adds to previous value)
8. ✅ StudentApp class with main() and Scanner
9. ✅ Accept student details from user
10. ✅ Display main menu
11. ✅ While loop for continuous menu
12. ✅ Choice 1 - View Student Details
13. ✅ Choice 2 - View Progress
14. ✅ Choice 3 - Add Completed Topics
15. ✅ Choice 4 - Add Solved Questions
16. ✅ Choice 5 - Exit with thank you message
17. ✅ Handle invalid menu choices

## Author

Created as part of the KodNest Fourth PRD Implementation project.