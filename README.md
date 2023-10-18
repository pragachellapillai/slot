# Ex03 Time Table

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

## CODE
```
<!DOCTYPE html>
<html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
        <center>
            <img src="logo.png" height="200" width="550">
        </center>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" bgcolor="Orange">
<caption><b>SLOT TIME TABLE -   PRAGAHARSHITHA NC(212222110033)</b></caption>
<tr align="center">
<th bgcolor="BLUE">Day/Time</th>
<th bgcolor="BLUE">8-10</th>
<th bgcolor="BLUE">10-12</th>
<th bgcolor="BLUE">12-1</th>
<th bgcolor="BLUE">1-3</th>
<th bgcolor="BLUE">3-5</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Monday</th>
<th bgcolor="Orange">SANM</th>
<th bgcolor="Orange">ES</th>
<th bgcolor="Orange" rowspan="6" align="center">LUNCH BREAK</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">PAQM</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Tuesday</th>
<th bgcolor="Orange">FWAD</th>
<th bgcolor="Orange">TOC</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">COM ENG</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Wednesday</th>
<th bgcolor="Orange">SANM</th>
<th bgcolor="Orange">SE</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">COM ENG</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Thrusday</th>
<th bgcolor="Orange">ES</th>
<th bgcolor="Orange">TOC</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">FWAD</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Friday</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">SNALT</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">PAQM</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Saturday</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">SE</th>
<th bgcolor="Orange">FWAD</th>
</tr>

</table>

<br>
<table align="center" cellspacing="2" cellpadding="4" border="4">
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
<td align="center">19EN101</td>
<td>Communicate English (COM ENG)</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19CS407</td>
<td>Theory of Computation (TOC)</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19AI521</td>
<td>Expert System (ES) </td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods(SANM)</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19MA222</td>
<td>Probability and Queueing Models(PAQM)</td>
</tr>

<tr>
<td align="center">7.</td>
<td align="center">19CS408</td>
<td>Software Engineering (SE)</td>
</tr>

<tr>
<td align="center">8.</td>
<td align="center">19EY703</td>
<td>System of Numerical and Logical Terminologies (SNALT)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT

![Screenshot (6)](https://github.com/pragachellapillai/slot/assets/148254952/a610c65f-ad53-4465-8e9f-bccd9b715510)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
