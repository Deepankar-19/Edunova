# Edunova
A step towards smarter, automated, and more efficient classrooms.

EduNova is a web-based smart classroom platform designed to automate attendance using real-time face detection, manage academic timetables, and support digital classroom workflows through role-based dashboards.

##**Features**

1)Real-time face-detection-based attendance using webcam

2)Role-based dashboards for Admin, Teacher, and Student

3)Automated timetable generation

4)Centralized and persistent attendance records

5)Scalable architecture for multi-class and multi-student environments


##**Tech Stack**

**Frontend*

1)HTML, CSS, JavaScript

2)React / Next.js

**Backend*

1)Node.js / FastAPI

2)REST APIs

**Database*

1)MongoDB

**AI / ML*

1)Face Detection (face-api.js)

2)Speech-to-text (for lecture transcripts)

##**System Workflow**

1)User logs in based on role (Admin / Teacher / Student)

2)Teacher initiates class and attendance session

3)Webcam detects faces and marks attendance

4)Attendance data is stored securely in the database

5)Students and faculty can view records in real time


##**Chatbot & Transcript Handling**

1)Lecture audio is converted to text using speech-to-text

2)Transcripts are stored class-wise in the database

3)Chatbot dynamically uses relevant transcripts as context to answer student queries

##**Project Status**

*In Development*
This project is actively being improved and extended with new features.

##**License**

This project is licensed under the MIT License.
