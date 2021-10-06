# Online Quiz

## screenshots
### Homepage
![homepage snap](https://github.com/sumitkumar1503/onlinequiz/blob/master/static/screenshots/homepage.png?raw=true)
### Admin Dashboard
![dashboard snap](https://github.com/sumitkumar1503/onlinequiz/blob/master/static/screenshots/adminhomepage.png?raw=true)
### Exam Rules
![invoice snap](https://github.com/sumitkumar1503/onlinequiz/blob/master/static/screenshots/rules.png?raw=true)
### Exam
![doctor snap](https://github.com/sumitkumar1503/onlinequiz/blob/master/static/screenshots/exam.png?raw=true)
### Teacher
![doctor snap](https://github.com/sumitkumar1503/onlinequiz/blob/master/static/screenshots/teacher.png?raw=true)
---
## Functions
### Admin
- Create Admin account using command
```
py manage.py createsuperuser
```
- After Login, can see Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Teacher
- Apply for job in System. Then Login (Approval required by system admin, Then only teacher can login).
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.
> **_NOTE:_**  Basically Admin Will Hire Teachers To Manage Courses and Questions.

### Student
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
