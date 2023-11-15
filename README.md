# Ex03 Time Table
## Date:08/11/2023

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
<title>slot timetable</title>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
 <table border="10" cellspacing="2"cellpadding="10"bgcolor="cyan">
<caption><h2> SLOT TIMETABLE Kishan Shree B (23012867)</h2></caption>
<tr>
<th bgcolor="red">Day/Time</th>
<th bgcolor="aquamarine">8-10</th>
<th bgcolor="aquamarine">10-12</th>
<th bgcolor="aquamarine">12-1</th>
<th bgcolor="aquamarine">1-3</th>
<th bgcolor="aquamarine">3-5</th>
</tr>
<tr>
<th bgcolor="magenta">Monday</th>
<td>EDM</td>
<td>Free Slot</td>
<td><rowspan="5">Break</rowspan></td>
<td>Soft Skills</td>
<td>Free Slot</td>
</tr>
<tr>
<th bgcolor="magenta">Tuesday</th>
<td>Free Slot</td>
<td>Linear Algebra</td>
<td>Break</td>
<td>Free Slot</td>
<td>Free Slot</td>
</tr>
</tr>
<th bgcolor="magenta">Wednesday</th>
<td>FWAD</td>
<td>EDM</td>
<td>Break</td>
<td>Free Slot</td>
<td>Python</td>

</tr>
<th bgcolor="magenta">Thursday</th>
<td>Free slot</td>
<td>FWAD</td>
<td>Break</td>
<td>C programming</td>
<td>Linear Algebra</td>
</tr>
<tr>
<th bgcolor="magenta">Friday</th>
<td>Python</td>
<td>C programming</td>
<td>Break</td>
<td>FWAD</td>
<td>Free Slot</td>
</tr>
</center>
</table>
<br>

 <table border="10" cellspacing="2"cellpadding="10">
<tr>
<th>S.NO</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<th>1</th>
<th>19AI414</th>
<th>Fundamentals Of Web Application</th>
</tr>
<tr>
<th>2</th>
<th>19AI301C</th>
<th>Python and Linear Algebra</th>
</tr>
<tr>
<th>3</th>
<th>19AI302</th>
<th>Engineering Design And Modelling</th>
</tr>
<tr>
<th>4</th>
<th>19AI414</th>
<th>Fundamentals Of C Programming</th>
</tr>
<tr>
<th>5</th>
<th>19EY701</th>
<th>Soft Skills</th>
</tr>
</body>
</html>
```


## OUTPUT
![Alt text](<Screenshot (10).png>)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
