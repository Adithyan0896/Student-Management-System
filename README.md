## Student Management System:


### Description:

This project involves designing a **relational database schema** for a **Student Management System **. The database includes essential tables to manage student information, courses, enrollments, grades, instructors, and course-instructor assignments. It supports functionalities for handling student registrations, course enrollments, grading, and instructor assignments efficiently.


### Features:

- **Student Management**: Handles storing and retrieving student details such as names, emails, contact information, and addresses.
  
- **Course Management**: Manages course details, including course names, descriptions, and credits.

- **Enrollment Management**: Tracks student enrollments in various courses and their respective enrollment dates.

- **Grade Management**: Stores student grades and GPAs for completed courses.

- **Instructor Management**: Stores instructor information, including contact details and department assignments.

- **Course-Instructor Assignment**: Links courses with the instructors teaching them.


### Database Schema:

The database consists of the following tables:

- **Students:** Stores details about the students, including student ID, name, contact details, and address.
  
- **Courses:** Contains information about the courses offered, including course ID, name, description, and credits.
  
- **Enrollments:** Links students to the courses they are enrolled in, with enrollment date.

- **Grades:** Contains students' grades and GPAs for each course they are enrolled in.

- **Instructors:** Stores information about instructors, including their ID, name, contact details, and department.

- **Course Instructors:** Links instructors to the courses they teach.


### Technologies Used:

- **SQL (MySQL)**: Used for creating and managing the relational database schema.

- **Relational Database Management System (RDBMS)**: A system to handle data integrity, relationships, and queries between different tables.


### Queries and Analysis:

The project includes various SQL queries and data analysis tasks to extract valuable insights from the student management data. Some of the key queries implemented include:

**1. JOIN:**  
   - Used to retrieve detailed information about students, their enrolled courses, grades, and instructors. For example, joining the Students, Enrollments, Courses, Grades, and Instructors tables to retrieve a list of students along with their grades, GPAs, and instructor names.

    

**2. VIEW:**  
   - Created a StudentTranscript view to generate a summarized report of students’ enrolled courses along with their grades and GPAs.

   
**3. SUBQUERY:**  
   - Used a subquery to find students who are enrolled in a specific course.

   
**4. STORED PROCEDURE:**  
   - Created a stored procedure to retrieve student transcripts, including course names, grades, and GPA for each student.

