# [Attendex - Attendance Management System]

## Overview
Attendex is a comprehensive web-based attendance management system developed using HTML, CSS, JavaScript, Firebase, and Node.js. It facilitates efficient attendance tracking for both administrators and students.
- The Attendance Management System is a web application designed for educational institutions to efficiently manage and monitor student attendance. The system is built using HTML, CSS, JavaScript, Firebase, and incorporates Node.js functionalities. It features separate interfaces for administrators/teachers and students.

### Features

#### Admin Panel
- **Attendance Monitoring:** View and manage attendance records of students.
- **QR Code Generation:** Generate daily QR codes for attendance marking.

#### Student Dashboard
- **Individual Attendance Records:** Access individual attendance history.
- **QR Code Scanner:** Scan the daily QR code to mark attendance.

### Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Firebase, Node.js
- **QR Code Generation:** qr.min.js

### Functionalities

#### Admin Side
- **Attendance Viewing:** Administrators can access and view attendance records of all students. The interface provides a comprehensive overview of attendance data.
- **QR Code Generation:** Daily QR codes are generated containing date information and expire within a few seconds to ensure validity for the current day's attendance.

#### Student Side
- **Individual Attendance Tracking:** Students can view their individual attendance records. This enables them to track their attendance history.
- **QR Code Scanning:** A scanner is provided for students to scan the daily QR code within the specified timeframe to mark their attendance for the day.

### Usage
- **Admin Side:** Upon login, administrators are directed to the dashboard where they can access attendance records and generate the daily QR code.
- **Student Side:** Students log in to view their attendance history and use the QR code scanner to mark daily attendance.

### Setup Instructions
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Set up Firebase configurations and database rules.
4. Run the application using `npm start` to launch the server.

### Future Enhancements
- Implement additional analytics and reporting features for administrators.
- Enhance security measures for QR code generation and scanning.

### Contributors
I'd like to acknowledge the following contributors who have dedicated their time and effort to this project:

- **[Ayesha Siddiqua](https://github.com/Ayesha-Siddiqua88)**
