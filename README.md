# Scan QR Speak Pass

I have made an employee card ,that contains some basic details. There is a QR at the below of the card. Scan the QR & if you are scanning it at 10 AM or between 12 Am-10 Am,you can see the message 'Welcome to work!" within an alert box. By any chance if you are late by 1 or more minutes then you can see the message "Sorry, you are late!" .
Details
Employee Card Description
This employee card is designed to display essential details about an employee along with a QR code that provides real-time feedback based on the time of scanning.

Components of the Employee Card:
Avatar Section:

Displays the employee's photo within a circular avatar.
The avatar is enhanced with a background color to make it stand out.
Employee Information:

Name: The full name of the employee.
Title: The employee's current designation or role.
ID: A unique identifier for the employee.
QR Code Section:

Positioned at the bottom of the card.
The QR code encodes a message that changes based on the current time.
Functionalities:
Time-Based Messages:

Welcome Message: If the QR code is scanned at exactly 10 AM or between 12 AM to 10 AM, the message "Welcome to work!" is displayed within an alert box.
Late Message: If the QR code is scanned even one minute past 10 AM, the message "Sorry, you are late!" is displayed within an alert box.
Real-Time Feedback:

The QR code functionality leverages the moment-timezone library to accurately determine the time in the specified timezone (Asia/Kolkata).
Upon scanning the QR code, the system checks the current time and displays the appropriate alert message based on the conditions mentioned above.
