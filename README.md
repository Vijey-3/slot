# Ex03 Time Table
## Date:
18/03/2024
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
<!DOCTYPE html>
<head>
    <title>SEC SLOT TIMETABLE</title>
</head>
<center>
<img src="logo.png" width='600' >
</center>
<body>
    <table BORDER='3' width='600'bgcolor='cyan' cellspacing='3' align="center">
        <CAPTION align="above">SLOT TIMETABLE-VIJEY K S(212223040239)</CAPTION>
        <tr>
            <th align="center" bgcolor="purple">Day/Time</th>
            <th align="center" bgcolor="purple">Monday</th>
            <th align="center" bgcolor="purple">Tuesday</th>
            <th align="center" bgcolor="purple">Wednesday</th>
            <th align="center" bgcolor="purple">Thursday</th>
            <th align="center" bgcolor="purple">Friday</th>
            <th align="center" bgcolor="purple">Saturday</th>
        </tr>

        <tr>
            <th align="center" bgcolor="purple">8-10</th>
            <td align="center" bgcolor="orange" colspan="2">FREE SLOT</td>
            <td align="center" bgcolor="orange">FWAD</td>
            <td align="center" bgcolor="orange">FREE SLOT</td>
            <td align="center" bgcolor="orange">EXPERT SYSTEMS</td>
            <td align="center" bgcolor="orange">PROBABILITY AND QUEUEING MODELS</td>
        </tr>

        <tr>
            <th align="center" bgcolor="purple">10-12</th>
            <td align="center" bgcolor="orange">FREE SLOT</td>
            <td align="center" bgcolor="orange">FWAD</td>
            <td align="center" bgcolor="orange">FREE SLOT</td>
            <td align="center" bgcolor="orange">PROBABILITY AND QUEUEING MODELS</td>
            <td align="center" bgcolor="orange">FUNDAMENTALS OF C PROGRAMMING</td>
            <td align="center" bgcolor="orange">FREE SLOT</td>
        </tr>

        <tr>
            <th align="center" bgcolor="purple">12-1</th>
            <td align="center" bgcolor="orange" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="purple">1-3</th>
            <td align="center" bgcolor="orange">FWAD</td>
            <td align="center" bgcolor="orange">PHYSICS FOR QUANTUM COMPUTING</td>
            <td align="center" bgcolor="orange">HRM</td>
            <td align="center" bgcolor="orange">EDM</td>
            <td align="center" bgcolor="orange">HRM</td>
            <td align="center" bgcolor="orange">FREE SLOT</td>
        </tr>


        <tr>
            <th align="center" bgcolor="purple">3-5</th>
            <td align="center" bgcolor="orange">FUNDAMENTALS OF C PROGRAMMING</td>
            <td align="center" bgcolor="orange">EDM</td>
            <td align="center" bgcolor="orange">FREE SLOT</td>
            <td align="center" bgcolor="orange">CREATIVE SKILLS FOR COMMUNICATION</td>
            <td align="center" bgcolor="orange" colspan="2">FREE SLOT</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="3" cellpaddling="3" align="center">

        <tr>
            <th align="center">S.NO</th>
            <th align="center">SUBJECT CODE</th>
            <th align="center">subject name</th>
        </tr>

        <tr>
            <td align="center">1</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19AI302</td>
            <td align="center">Engineering designing and modelling</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19AI304</td>
            <td align="center">Fundamentals of C programming</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19AI521</td>
            <td align="center">Expert systems</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19EY702</td>
            <td align="center">Creative skills for communication</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19MA222</td>
            <td align="center">Probability and Queueing models</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19MS156</td>
            <td align="center">Human resource management and team building</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19PH214</td>
            <td align="center">Physics for quantum computing</td>
        </tr>
    </body>
    </html>
```

## OUTPUT
![alt text](<Screenshot (19).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
