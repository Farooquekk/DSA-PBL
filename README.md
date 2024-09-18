# 📚 Student Performance Data Management System 📊

Welcome to the **Student Performance Data Management System**! This project is designed to demonstrate the practical application of Data Structures and Algorithms (DSA) in analyzing and managing student performance data. The system processes real-world student performance records and performs operations such as sorting, queuing, stacking, and calculating statistical insights. 🌟

## 🚀 Project Overview

This project simulates a system that reads data from a file containing student performance information. It utilizes advanced data structures like **Linked Lists**, **Stacks**, and **Queues** to analyze and organize the data efficiently. The core functionalities include sorting students by their average scores, categorizing them by their gender and parental education level, and calculating various statistics such as median scores and gender-wise performance at different parental education levels.

### 🔧 Key Features

1. **File Parsing and Data Loading** 📂
   - Reads and parses student data from a CSV file (e.g., *StudentsData.txt*) with attributes like gender, group, parental education level, and scores in math, reading, and writing.

2. **Data Structures Used** 🛠️
   - **Linked Lists**: Manage student records efficiently.
   - **Stacks**: Used to handle and reverse the order of students.
   - **Queues**: Organize students by parental education levels and study groups for performance comparison.

3. **Sorting Algorithm** 📈
   - Implements **Bubble Sort** to arrange students by their average marks.

4. **Statistical Analysis** 📊
   - **Median Calculation**: Finds the median average score for male and female students.
   - **Best Group Performance**: Identifies the group with the highest average performance.
   - **Gender-wise Performance**: Compares male and female student performance at different parental education levels.
   - **Group Performance by Parental Level**: Analyzes how students from different groups perform at various parental education levels.

5. **Visualization and Output** 📋
   - Displays detailed student records, sorted lists, and group-wise performance through formatted console output.

## 🧠 Core Concepts

### Data Structures and Algorithms
- **Linked List**: Used to store student records dynamically.
- **Stack**: Allows Last-In-First-Out (LIFO) operations for students, useful for reverse traversal and performance.
- **Queue**: Implements First-In-First-Out (FIFO) for grouping students by various attributes, helping in managing groups or categories efficiently.
- **Sorting**: Bubble sort is used to order students by their average marks.

### Problem Solving
The project addresses several real-world problems using DSA:
- **Gender Performance**: Determines which gender performs better at different parental education levels.
- **Group Analysis**: Compares the performance of various groups (e.g., Group A, B, C) to find the one with the best results.
- **Median Score**: Computes the median of average scores for both male and female students.

## 🎯 How It Works

1. **Data Ingestion**:
   - The system reads from a file containing student performance data in CSV format.
   - It processes each student's gender, group, parental education, and test scores.
   
2. **Categorization**:
   - The students are categorized into **Male** and **Female** linked lists based on their gender.
   
3. **Sorting**:
   - Each list is sorted based on the average of the three test scores: Math, Reading, and Writing.

4. **Stack Operations**:
   - After sorting, the students are pushed into **Stacks** for easier access and manipulation in later operations.

5. **Queue Operations**:
   - The system creates queues to group students by **Parental Education Level** and **Groups** (A, B, C, etc.) for performance comparison.

6. **Statistical Analysis**:
   - The system calculates and outputs:
     - The **median** score for male and female students.
     - The **best-performing group** based on average scores.
     - The **performance comparison by parental level** and gender.

## 📄 File Structure

```
📂 DSA_PBL
│
├── 📄 StudentsData.txt          # Input file containing student data
├── 📄 Main.java                 # Main program entry point
├── 📄 Node.java                 # Class for Linked List nodes
├── 📄 StackOfStudents.java      # Class to implement stack operations on students
├── 📄 QueueForGroups.java       # Class to manage group-based queue operations
├── 📄 QueueForParentalLevel.java# Class to manage parental-level based queues
├── 📄 Student.java              # Class representing the Student object
└── 📄 README.md                 # You are here!
```

## 🔥 Getting Started

### Prerequisites

To run this project, ensure you have:
- **Java Development Kit (JDK)** installed
- A **Java IDE** like IntelliJ IDEA, Eclipse, or any text editor with Java support
- The **StudentsData.txt** file with the following structure:
  ```
  Gender,Group,Parental Education,Lunch,Test Preparation,Math Score,Reading Score,Writing Score
  "female","group B","bachelor's degree","standard","none",72,72,74
  ```

### Running the Project

1. Clone the repository or download the project files.
2. Open the project in your favorite IDE.
3. Make sure the `StudentsData.txt` file is in the correct location.
4. Run the `Main` class to execute the program.

## 💻 Sample Output

```
**************************************************************************************
Sorted Male Students:
Student{gender='male', group='group C', parentalLevel='associate's degree', mathScore=65, readingScore=70, writingScore=68, averageScore=67.67}
...

Sorted Female Students:
Student{gender='female', group='group B', parentalLevel='bachelor's degree', mathScore=72, readingScore=72, writingScore=74, averageScore=72.67}
...

Best Avg Marks Of Group A: 78.5
Best Avg Marks Of Group D: 82.0

Performance Of Male at Parental Level "bachelor's degree": 70.4
Performance Of Female at Parental Level "bachelor's degree": 75.6
Female performs better.
...
**************************************************************************************
```

## 📈 Future Enhancements

- **Graphical User Interface (GUI)** for better interaction.
- **Advanced Sorting Algorithms** to improve performance for large datasets.
- **Integration with a Database** for persistent data storage and retrieval.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request with any improvements or additional features you think would be beneficial.

## 👨‍💻 Authors

This project was developed by **[Farooque Sajjad]** as part of the 3rd-semester DSA course project. 🌱

---

<div align="center">

### 🎉 Thank you for checking out the project! 🎉

</div>
