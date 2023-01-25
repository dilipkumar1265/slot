# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag

### STEP 2
Add header row using th tag

### STEP 3
Add your timetable

### STEP 4
Execute the program


# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - DILIP KUMAR R (22008361)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>C in P1</td>
<td colspan="1">FREE SLOT</td>
<td>ED and M</td>
<td colspan="1">FREE SLOT</td>
<td>Chem</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>ED and M</td>
<td> Eng </td>
<td>Web</td>
<td>Web</td>
<td>Web</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>Soft skills</td>
<td>Maths</td>
<td colspan="1"> FREE SLOT </td>
<td>Eng</td>
<td>Maths</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="1"> FREE SLOT </td>
<td>C in P1</td>
<td>FREE SLOT</td>
<td>Chem</td>
<td>Web</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">12EY701</td>
<td>Soft Skills(Soft skills)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (Chem)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EN101</td>
<td>Communicative English(Eng)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI302</td>
<td>Engineering Design And Modelling(ED and M)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19MA201</td>
<td>Calculus and Matrix Algebra</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS302P1</td>
<td>Programming in C P1(C in P1)</td>
</tr>
</table>
</body>
</html>
```

# OUPUT
![OUTPUT](./ou.png)

# HTML VALIDATOR
![HTML VALIDATOR](valid.png)

# RESULT 
The program is executed successfully