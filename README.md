# PROG101_Assignment1_SolomonHamusasesay_905006510
This is assignment 1 for programming logic and design about School Attendance Management System
## Project Information
# School Attendance Management System (SAMS)
## Project Title
School Attendance Management System (SAMS)

## Problem Description
Many schools in Sierra Leone still use paper attendance registers to record students' attendance. This method can be slow, and records may sometimes be lost, damaged, or recorded incorrectly. Teachers may also find it difficult to calculate attendance percentages or check a student's attendance history.
The School Attendance Management System (SAMS) is designed to help solve these problems. The system will allow teachers to register students, record daily attendance, search for student records, and generate attendance reports. This will make attendance management easier, faster, and more organised.

## Community Impact
The School Attendance Management System (SAMS) will benefit schools, teachers, students, and parents in Sierra Leone.
The system will help teachers save time when recording attendance and reduce mistakes in keeping records. School administrators will be able to monitor student attendance and identify students who are frequently absent.
Students will benefit because schools can identify attendance problems early and provide support. Parents may also be informed when their children are regularly absent from school.
Overall, SAMS can help schools improve record keeping, encourage regular attendance, and support better education in the community.

## SDG Alignment
The School Attendance Management System (SAMS) supports **Sustainable Development Goal 4 (SDG 4): Quality Education**.
SDG 4 aims to ensure inclusive and equitable quality education and promote learning opportunities for everyone.
SAMS supports this goal by helping schools monitor student attendance and identify students who are frequently absent. This allows teachers and school administrators to take early action and encourage students to attend classes regularly.
The system can also improve school record keeping and help administrators make better decisions using attendance information.
By supporting regular attendance and better school management, SAMS can contribute to improving education in Sierra Leone.

## Pseudocode of the School Attendance Management System (SAMS)
BEGIN
    DISPLAY "SCHOOL ATTENDANCE MANAGEMENT SYSTEM"

    REPEAT
        DISPLAY "1. Register Student"
        DISPLAY "2. Record Attendance"
        DISPLAY "3. Search Records"
        DISPLAY "4. Generate Report"
        DISPLAY "5. Exit"

        INPUT choice

        IF choice = 1 THEN
            CALL StudentRegistration
        ELSE IF choice = 2 THEN
            CALL RecordAttendance
        ELSE IF choice = 3 THEN
            CALL SearchRecords
        ELSE IF choice = 4 THEN
            CALL GenerateReport
        ELSE IF choice = 5 THEN
            DISPLAY "Thank you for using SAMS"
        ELSE
            DISPLAY "Invalid choice"
        END IF

    UNTIL choice = 5
END
