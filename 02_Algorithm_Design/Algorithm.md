# Algorithm Design
## 1. Main System Algorithm
     Start the system.
     Display the main menu.
      Ask the user to choose an option.
     Check the option selected.
     If the user selects registration, open student registration.
     If the user selects attendance, open attendance recording.
     If the user selects search, open student record search.
     If the user selects reports, generate an attendance report.
     If the user selects exit, close the system.
     If an invalid option is entered, display an error message.
     Return to the main menu when an operation is completed.
## 2. Student Registration Algorithm
     Start the registration process.
     Ask the user to enter the student's ID.
     Ask for the student's full name.
     Ask for the student's class.
     Check whether all required details have been entered.
     Check whether the student ID already exists.
     If the ID already exists, display an error message.
     Otherwise, save the student's details.
     Display a successful registration message.
     End the registration process.
## 3. Attendance Recording Algorithm
       Start the attendance recording process.
       Enter the student's ID.
       Search for the student in the system.
       Check if the student is registered.
       If the student is not registered, display an error message.
       If registered, display the student's details.
       Select the attendance status (Present or Absent).
       Save the attendance record with the date.
       Display a successful message.
       End the process.
## 4. Search Records Algorithm
       Start the search process.
       Ask the user to enter the student's ID.
       Search for the ID in the attendance records.
       Check whether the record exists
       If the record is found, display the student's details and attendance history.
       If the record is not found, display a message saying the student does not exist.
       End the search process.
## 5. Report Generation Algorithm
       Start the report generation process.
       Ask the user to select a student or class.
       Enter the required student ID or class.
       Retrieve the attendance records.
       Count the total number of days the student was present.
       Count the total number of days the student was absent.
       Calculate the attendance percentage.
       Display the attendance report.
       End the process.
