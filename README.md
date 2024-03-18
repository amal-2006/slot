# Ex03 Time Table
## Date: 18.03.2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
</head>
    <title> Slot Timetable</title>
</head>
<body>
    <center>
        <img src="logo.png" height="100" width="550">
    </center>
    <br>
    <table align="center" width="550" cellspacing="2" cellpadding="4" border="4" bgcolor="lavender">
        <caption><b>Timetable - AMALJOSH MAADHAV J (23014023)</b></caption>
    <tr align="center">
        <th bgcolor="plum">Day/Time</th>
        <th bgcolor="plum">Monday</th>
        <th bgcolor="plum">Tuesday</th>
        <th bgcolor="plum">Wednesday</th>
        <th bgcolor="plum">Thursday</th>
        <th bgcolor="plum">Friday</th>
        <th bgcolor="plum">Saturday</th>
    </tr>
    <tr align="center">
        <th bgcolor="plum">8-10</th>
        <td>FREE SLOT</td>
        <td>INTRODUCTION TO MACHINE LEARNING</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
        <td>INTRODUCTION TO MACHINE LEARNING</td>
        <td>FREE SLOT</td>
    </tr>
    <tr align="center">
        <th bgcolor="plum">10-12</th>
        <td>PROGRAMMING MICROCONTROLLERS</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>PHYSICS FOR QUANTUM COMPUTING</td>
        <td>FREE SLOT</td>
        <td>CREATIVE SKILLS FOR COMMUNICATION</td>
        <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
    </tr>
    <tr>
        <th bgcolor="plum">12-1</th>
        <td colspan="6" align="center">L  U  N  C  H</td>
    </tr>
    <tr align="center">
        <th bgcolor="plum">1-3</th>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td colspan="2">FREE SLOT</td>
        <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
        <td>PROGRAMMING MICROCONTROLLERS</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
    </tr>
    <tr align="center">
        <th bgcolor="plum">3-5</th>
        <td>ADVANCED C PROGRAMMING</td>
        <td>PHYSICS FOR QUANTUM COMPUTING</td>
        <td>ADVANCED C PROGRAMMING</td>
        <td colspan="3">FREE SLOT</td>
    </tr>
    </table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
    <tr align="center">
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td align="center">1.</td>
        <td align="center">19AI303</td>
        <td>Engineering Mechanics and Product Development</td>
    </tr>
    <tr>
        <td align="center">2.</td>
        <td align="center">19AI410</td>
        <td>Advanced C Programming</td>
    </tr>
    <tr>
        <td align="center">3.</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td align="center">4.</td>
        <td align="center">19EE309</td>
        <td>Programming Microcontrollers</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19EY702</td>
        <td>Creative Skills for Communication</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19MA211</td>
        <td>Statistics and Numerical Methods</td>
    </tr>
    <tr>
        <td align="center">7.</td>
        <td align="center">19PH214</td>
        <td>Physics for Quantum Computing</td>
    </tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Slot Timetable.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
