# Ex03 Time Table
## Date: 18/03/2024

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
<th bgcolor="Orange">DS</th>
<th bgcolor="Orange">BEE</th>
<th bgcolor="Orange" rowspan="6" align="center">LUNCH BREAK</th>
<th bgcolor="Orange">FWAD</th>
<th bgcolor="Orange">C</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">TuesdaY</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">FWAD</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">PMC</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Wednesday</th>
<th bgcolor="Orange">FWAD</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">DBMS</th>
<th bgcolor="Orange">CN</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Thrusday</th>
<th bgcolor="Orange">DIP</th>
<th bgcolor="Orange">FREE SLOT</th>
<th bgcolor="Orange">BEE</th>
<th bgcolor="Orange">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Friday</th>
<th bgcolor="Orange">DIP</th>
<th bgcolor="Orange">C</th>
<th bgcolor="Orange">CN</th>
<th bgcolor="Orange">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="BLUE">Saturday</th>
<th bgcolor="Orange">DS</th>
<th bgcolor="Orange">PMC</th>
<th bgcolor="Orange">DBMS</th>
<th bgcolor="Orange">FREE SLOT</th>
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
<td align="center">19EE305</td>
<td>Basic Electric And Electronic Measurement(BEE)</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>Computer Networks(CN)</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19EE309</td>
<td>Programming Micro ControLler(PMC) </td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19AI403</td>
<td>Intoduction To Data Science(DS)</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19AI304</td>
<td>Fundamentals Of C Programming(C)</td>
</tr>

<tr>
<td align="center">7.</td>
<td align="center">19CS404</td>
<td>Database Management System and its applicaton(DBMS)</td>
</tr>

<tr>
<td align="center">8.</td>
<td align="center">19CS406</td>
<td>Computer Networks(CN)</td>
</tr>
<tr>
    <td align="center">9.</td>
    <td align="'center">19AI406</td>
    <td>Digital Image Processing Techniques(DIP)</td>
</tr>
</table>
</body>
</html>
```
OUTPUT:
![WhatsApp Image 2024-03-18 at 22 29 31_e9de99ac](https://github.com/pragachellapillai/slot/assets/148254952/69dd11b3-8126-4af8-8525-7ebe21cdf2b6)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
