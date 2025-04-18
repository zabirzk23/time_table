# Ex03 Time Table
# Date: 18-04-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

```
<html>
<head>
<title> SLOT TIMETABLE </title>
</head>
<body>
    <center><img src="/static/logo.png" height="100" width="570"></center>
<br>
<table align="center" width="600" cellspacing="4" cellpadding="5" border="4" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - MOHAMED ZABIR KHAN A(24900623)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">8-10</th>
<th bgcolor="yellow">10-12</th>
<th rowspan="7" bgcolor="yellow">L U N C H</th>
<th bgcolor="yellow">1-3</th>
<th bgcolor="yellow">3-5</th>
</tr>
<tr align="center">
<th bgcolor="yellow">MONDAY</th>
<td >FUNDAMENTALS OF AI</td>
<td> FREE SLOT</td>
<td> DIGITAL ELECTRONICS</td>
<td rowspan="2">FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">TUESDAY</th>
<td rowspan="5">FREE SLOT</td>
<td> FUNDAMENTALS OF WEB </td>
<td> PROBABILTY AND QUEUEING MODELS</td>
</tr>
<tr>
<th bgcolor="yellow">WEDNESDAY</th>
<td> DIGITAL ELECTRONICS</td>
<td> MENTOR MEET</td>
<td >FUNDAMENTALS OF AI</td>
</tr>
<tr align="center">
<th bgcolor="yellow">THURSDAY</th>
<td> PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td rowspan="3">FREE SLOT</td>
</tr>
<tr align="center">
<th  bgcolor="yellow">FRIDAY</th>
<td> PRINCIPLES OF CHEMISTRY IN ENGINEERING </td>
<td> PROBABILTY AND QUEUEING MODELS</td>
</tr>
</tr>
<tr align="center">
<th  bgcolor="yellow">SATRUDAY</th>
<td> FUNDAMENTALS OF C PROGRAMMING</td>
<td> FUNDAMENTALS OF WEB APPLICATION</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th bgcolor="yellow">S. No.</th>
<th bgcolor="yellow">Subject Code</th>
<th bgcolor="yellow">Subject Name</th>
</tr>
<tr>
<td bgcolor="lightblue" align="center">1.</td>
<td bgcolor="lightblue" align="center">19AI414</td>
<td bgcolor="lightblue">FUNDAMENTALS OF WEB APPLICATION</td>
</tr>
<tr>
<td  bgcolor="lightblue"align="center">2.</td>
<td  bgcolor="lightblue" align="center">19AI304</td>
<td bgcolor="lightblue">FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">3.</td>
<td bgcolor="lightblue" align="center">19CY205</td>
<td bgcolor="lightblue"> PRINCIPLES OF CHEMISTRY IN ENGINEERING </td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">4.</td>
<td bgcolor="lightblue" align="center"> 19EE404 </td>
<td bgcolor="lightblue">DIGITAL ELECTRONICS</td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">5.</td>
<td bgcolor="lightblue" align="center">19AI405</td>
<td bgcolor="lightblue">FUNDAMENTALS OF AI</td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">6.</td>
<td bgcolor="lightblue" align="center"> 19MA222</td>
<td bgcolor="lightblue">PROBABILTY AND QUEUEING MODELS</td>
</tr>
</table>
</body>
</html>

```
# OUTPUT

![alt text](<timetable ss.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
