# Sama school
### 1. Management System:
 sama school provides a simple and organized way to manage school information.Users can add new students, teachers, and courses, edit existing information, and delete records when they are no longer needed. This feature helps keep school data organized, makes information easier to access, and allows users to manage school records more efficiently.

### 2. Data Managemnt:
Sama School helps users manage and maintain school records by saving changes made to the system. Whenever users add new information, edit existing records, or delete unnecessary data, they can save their changes to keep the information up to date. This feature helps prevent changes from being lost and ensures that school records remain organized and consistent.

### 3. Classroom Management:
Sama School provides a classroom management feature that allows users to create classrooms by entering a unique ID and a name for each classroom. Users can select teachers from the list of existing teachers and assign students with scores below 10 to the selected teacher. This feature helps organize classrooms, manage teacher assignments, and identify students who may need additional academic support.

## classes
- # Student
| property | description |
| --- |---|
|ID |A unique identifier assigned to each student.|
|name|The first name of the student.|
|family|The family name (last name) of the student.|
|courses|A list of courses assigned to the student.|

- # Teacher
| property | description |
| --- |---|
|ID|A unique identifier assigned to each teacher.|
|name|The first name of the teacher.|
|family|The family name (last name) of the teacher.|
|grade|The grade assigned to the teacher.|
|courses|A list of courses taught by the teacher.|

- # Course
| property | description |
| --- |---|
|ID|A unique identifier assigned to each course.|
|name|The name of the course.|
|units|The number of academic units assigned to the course.|

- # School
| property | description |
| --- |---|
|name|The name of the school.|
|courses|A list of courses available in the school.|
|teacher|A list of teachers working at the school.|
|student|A list of students registered at the school.|
|classrooms|A list of classrooms created in the school.|
|selected_student|The currently selected student, or None if no student is selected.|
|selected_teacher|The currently selected teacher, or None if no teacher is selected.|
|selected_course|The currently selected course, or None if no course is selected.|

- # Classroom
| property | description |
| --- |---|
|ID|A unique identifier assigned to each classroom.|
|name|The name of the classroom.|
|course|The course assigned to the classroom, or None if no course is assigned.|
|teacher|The teacher assigned to the classroom, or None if no teacher is assigned.|
|student|A list of students assigned to the classroom.|