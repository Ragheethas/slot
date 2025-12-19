# Ex03 Time Table
## Date:10/12/25

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
<html>
<head>
    <title>Slot Time Table - S RAGHEETHA(25000507)</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - RAGHEETHA</h3>

    <table border="1">
        <tr BGCOLOR="BLUE">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
	    <th>Saturday</th>

        </tr>
        <tr BGCOLOR="RED">
            <td BGCOLOR="BLUE">8-10</td>
            <td>PUBLIC SPEAKING</td>
            <td>FREE</td>
            <td>PUBLIC SPEAKING</td>
            <td>FREE</td>
            <td>FREE</td>
	    <td>FREE</td>
        </tr>
        <tr BGCOLOR="RED">
            <td BGCOLOR="BLUE">10-12</td>
            <td>FREE</td>
            <td>FREE</td>
            <td>FWAD</td>
            <td>FREE</td>
            <td>WEB</td>
	    <td>WEB</td>

        </tr>
        </tr>
        <tr BGCOLOR="RED">
            <td BGCOLOR="BLUE">12-1</td>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="RED">
            <td BGCOLOR="BLUE">1-3</td>
            <td>FWAD</td>
            <td>PUBLIC SPEAKING</td>
            <td>MENTOR MEET</td>
            <td>PUBLIC SPEAKING</td>
            <td>WEB</td>
	    <td>FREE</td>
        </tr>
        <tr BGCOLOR="RED">
            <td BGCOLOR="BLUE">3-5</td>
            <td>PYTHON</td>
            <td>PYTHON</td>
            <td>PYTHON</td>
            <td>PYTHON</td>
            <td>FREE</td>
	    <td>PYTHON</td>
        </tr>
	
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN105</td>
            <td>Public Speaking (PS)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI301</td>
            <td>Python (PY)</td>
        </tr>
            </table>
</body>
</html>
```



## OUTPUT

![alt text](<Screenshot 2025-12-10 115120.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
