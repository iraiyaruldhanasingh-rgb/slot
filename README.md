# Ex02 Time Table
## Date: 16/03/26

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title>Time Table</title>
</head>

<body bgcolor="lightgrey">

<center>
<img src="logo.png" width="350" height="90">
</center>

<table border="2" bgcolor="lavender" cellspacing="8" cellpadding="5">

<caption><b>SLOT TIME TABLE - IRAIARUL (25012197)</b></caption>

<tr bgcolor="orange">
<th>Day / Time</th>
<th>Mon</th>
<th>Tue</th>
<th>Wed</th>
<th>Thu</th>
<th>Fri</th>
<th>Sat</th>
</tr>

<tr>
<td bgcolor="lightyellow" align="center">8 - 10</td>
<td align="center">Web</td>
<td align="center">C Prog</td>
<td align="center">Web</td>
<td align="center">--</td>
<td align="center">Web</td>
<td align="center">--</td>
</tr>

<tr>
<td bgcolor="lightyellow" align="center">10 - 12</td>
<td>C Programming</td>
<td>Web</td>
<td align="center">Nil</td>
<td align="center">Nil</td>
<td>C Programming</td>
<td>Web</td>
</tr>

<tr bgcolor="lightgreen">
<td align="center">12 - 1</td>
<td colspan="6" align="center"><b>LUNCH BREAK</b></td>
</tr>

<tr>
<td bgcolor="lightyellow" align="center">1 - 3</td>
<td>Nil</td>
<td>Nil</td>
<td align="center">Mentor</td>
<td>C Programming</td>
<td align="center">Nil</td>
<td>C Programming</td>
</tr>

</table>

<br><br>

<table border="2" cellspacing="6" cellpadding="4" bgcolor="white">

<tr bgcolor="skyblue">
<th>S.No</th>
<th>Code</th>
<th>Subject</th>
</tr>

<tr>
<td align="center">1</td>
<td>19AI414</td>
<td>Fundamentals of Web App Development</td>
</tr>

<tr>
<td align="center">2</td>
<td>19AI304</td>
<td>Fundamentals of C Programming</td>
</tr>

</table>

</body>
</html>
```

## OUTPUT
<img width="1919" height="1079" alt="Screenshot 2026-03-31 151244" src="https://github.com/user-attachments/assets/923e198e-1471-4464-a16a-a41e63f3a139" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
