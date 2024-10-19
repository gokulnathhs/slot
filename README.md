# Ex03 Time Table
## Date:

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


<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>

<br>
<table align="center" width="750" cellspacing="2" cellpadding="4" border="5" bgcolor="grey">
<caption><i><b><h3>SLOT TIME TABLE - GOKULNATH H (212222040045)</h3><b></i></caption>
<tr align="center">
<th bgcolor="red">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wednesday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
<th bgcolor="green">Saturday</th>
</tr>

<tr align="center">
<th bgcolor="red">8-10</th>
<td>QA-1</td>
<td>MPMC</td>
<td>MPMC</td>
<td>DBMS</td>
<td>CC</td>
<td>FWAD</td>
</tr>

<tr align="center">
<th bgcolor="red">10-12</th>
<td>DBMS</td>
<td>VCC</td>
<td></td>
<td>FWAD</td>
<td></td>
<td></td>
</tr>

<tr>
<th bgcolor="red">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>

<tr align="center">
<th bgcolor="red">1-3</th>
<td colspan="1">EES</td>
<td>COM ENG</td>
<td>MENTOR MEET</td>
<td></td>
<td>CE</td>
<td></td>
</tr>

<tr align="center">
<th bgcolor="red">3-5</th>
<td colspan="1">FWAD</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td>MPMC</td>
</tr>

</table>
<br>
<table align="center" width="750" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td align="center">1.</td>
<td align="center">19EY710</td>
<td>QA-1</td>
</tr>

<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>FWAD</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19CS404</td>
<td>DBMS</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19EC307</td>
<td>CE</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19EC408</td>
<td>MPMC</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19EY411</td>
<td>VCC</td>
</tr>

<tr>
<td align="center">7.</td>
<td align="center">ECA-M</td>
<td>MENTOR MEET</td>
</table>
</body>
</html>

## OUTPUT
![Screenshot 2024-10-19 200450](https://github.com/user-attachments/assets/00a7be04-0524-4882-a8e2-16573a8ae95d)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
