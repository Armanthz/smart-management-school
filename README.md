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
---
# how it wotks?
when you open this app you saw this menu:
```python
1.students
2.teachers
3.courses
4.classrooms
5.save
0.exit
>>:
```
when you chose number1 you can work with studends
number2:you can work with teachers
number3:you can see course
number4:you can work with classrooms
number5 save the edites
number 0 close the app
--- 
```python
1.show students
2.add student
3.edit student
4.delete studnet
5.select student
0.back
>>:
```
---
now you see this menu
number 1 show you all of student
number2 add a new student
number3 you chose a student and edit it
number4 you chose a student for delet
number 5 you chose a student
and the end number0 leave the Page
---
## when you use number 2:
```python
1.show teachers
2.add teacher
3.edit teacher
4.delete teacher
5.select teacher
0.back
>>:
```
---
now you see this menu
number 1 show you all of teacher
number2 add a new teacher
number3 you chose a teacher and edit it
number4 you chose a teacher for delet
number 5 you chose a teacher
and the end number0 leave the Page
---
# Number3:
```python
1.show courses
2.add course
3.edit course
4.delete course
0.back
```
---
now you see this menu
number 1 show you all of course
number2 add a new course
number3 you chose a course and edit it
number4 you chose a course for delet
number 5 you chose a course
and the end number0 leave the Page
---
# Number4:
```python
1.show classrooms
2.add classroom
3.edit classroom
4.delete classroom
5.select classroom
0.back
```
now you see this menu
number 1 show you all of classroom
number2 add a new classroom
number3 you chose a clasroom and edit it
number4 you chose a classroom for delet
number 5 you chose a classroom
and the end number0 leave the Page
---
# Nmber5
save the edits
---
#number0
exit
---