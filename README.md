School Management System

The School Management System is an application developed using the Python programming language. Its main purpose is to make school management easier and more organized. This program helps the school principal manage different school activities and access important information easily.

This project includes features such as registering student information, managing teachers, recording grades, checking academic performance, managing classes, and viewing personal information. These features make school tasks faster and easier and reduce the need for manual record-keeping.

The main goal of this project is to create a simple and useful system for managing a school and improving Python programming skills. It also helps develop important programming skills such as using conditions, loops, functions, lists, and data management in Python.
# Classes and Their Responsibilities

## 1. Course

| Property | Description |
|---|---|
| `id` | A unique identifier used to find and identify a course. |
| `name` | The name of the course. |
| `units` | The number of units assigned to the course. |
| `score` | Stores the student's score for the course. |

| Method | Description |
|---|---|
| `__init__()` | Initializes a course with an ID, name, and number of units. |
| `__eq__()` | Compares two courses using their IDs. |

## 2. Student

| Property | Description |
|---|---|
| `id` | A unique identifier for the student. |
| `name` | The student's first name. |
| `family` | The student's family name. |
| `courses` | A list of courses assigned to the student. |

| Method | Description |
|---|---|
| `__init__()` | Initializes a student. |
| `__eq__()` | Compares two students using their IDs. |

## 3. Teacher

| Property | Description |
|---|---|
| `id` | A unique identifier for the teacher. |
| `name` | The teacher's first name. |
| `family` | The teacher's family name. |
| `grade` | The teacher's grade or qualification. |
| `courses` | A list of courses assigned to the teacher. |

| Method | Description |
|---|---|
| `__init__()` | Initializes a teacher. |
| `__eq__()` | Compares two teachers using their IDs. |

## 4. Classroom

| Property | Description |
|---|---|
| `id` | A unique identifier for the classroom. |
| `name` | The classroom's name. |
| `course` | The course taught in the classroom. |
| `teacher` | The teacher assigned to the classroom. |
| `students` | A list of students in the classroom. |

| Method | Description |
|---|---|
| `__init__()` | Initializes a classroom with an ID and name. |
| `__eq__()` | Compares two classrooms using their IDs. |

## 5. School

| Property | Description |
|---|---|
| `name` | The name of the school. |
| `courses` | Stores all courses available in the school. |
| `teachers` | Stores all teachers registered in the school. |
| `students` | Stores all students registered in the school. |
| `selected_student` | Stores the currently selected student. |
| `selected_teacher` | Stores the currently selected teacher. |

| Method | Description |
|---|---|
| `__init__()` | Initializes the school. |
| `add_student()` | Adds a new student if their ID doesn't already exist. |
| `delete_student()` | Removes a student using their ID. |
| `add_teacher()` | Adds a new teacher if their ID doesn't already exist. |
| `delete_teacher()` | Removes a teacher using their ID. |
| `load_data()` | Loads courses, students, and teachers from a JSON file. |
| `save_data()` | Saves courses, students, and teachers into a JSON file. |

