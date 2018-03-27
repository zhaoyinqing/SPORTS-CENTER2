
SA46TEAM04B - Sports Facility Booking System

Team Members: 
A0180510W	THARRANI UDHAYASEKAR
A0180603N	YANG XU
A0180507J	ZHAO YINQING


Roles:
Database Creation & Maintenance - Tharrani
Add Members Form, Update Members (All & Select) Forms, Booking Summary Report - Tharrani
Booking Facility Form, Cancel Facility Form, Member List Report - Zhao
Add Facility Form, Update Facility Form, Slot Availability Report - Yang Xu
Booking Receipt Report - Team

Assumptions for business rules:
* All transactions are to be carried out by employees. 
* Facility can be booked only by existing members. Hence new user must register as a member before he/she can avail booking.
* Each facility can be accessed for 12 hour a day in one hour slot (6 AM - 6 PM). Hence total 12 slots.
* Booking can be done only for tomorrow.
* Cancel will not delete the transaction details. It will only change flag.
* All reports are accessible to all employees (no restriction defined for User Access level).
* Each user has 3 login attempt and User ID and password is to be entered into Database prior to system launch.
* Members are classified as A (>100$), B(50-100$), C(<50$) based on their amount spend.
* All prices are in SGD.
* Members created in system are not allowed to be deleted by the employee.

Scope:

Below Processes are not covered in this project by the team:

Out of scope:
-System Admin to reset password
-Financial transaction - payment method
-Addition of new Employee with default login password
-Restriction of user input in text box as per database datatype
-Classifying members as A,B,C by business logic at end of each day/week

Notes:

LoginName	Password
Tharrani	T001
Yang		X002
Zhao		Z003

* All the forms are inherited from Parent Form which is in Form Template.dll. The parent form Form1 contains background picture, icon.
* Member ID, Facility ID, Booking ID are given as Identity Specifier in Database (Hence we have not utilised ControlTable though it is avaialble in DB).
* Exceptions are handled in few cases. It is not fully validated and handled for all user input controls throughout the project.
* we were not able to link ComboBox options from Database rows. Hence we have hard-coded the combo box options


