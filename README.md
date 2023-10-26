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
<html lang="en">
<head>
<title>Project Exhibition Schedule</title>
</head>
<body>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>Project Exhibition Schedule</b></caption>
<caption><b>KAMALI.E (212222110015)</b></caption>
</table>
</br>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<td colspan="2" bgcolor="cyan">Reg No:212222110015</td>
<td colspan="5" bgcolor="cyan" >Name: KAMALI.E</td>
</tr>



</tr>
<tr align="center">
<th bgcolor="yellow">Date/Time</th>  
<th bgcolor="yellow">monday</th>    
<th bgcolor="yellow">tuesday</th>
<th bgcolor="yellow">wednesday</th>
<th bgcolor="yellow">thursday</th>
<th bgcolor="yellow">friday</th>
</tr>
<tr>
<td align="center">8-10</td>
<td bgcolor="cyan">colspan="3" align ="center">FREE SLOT</td>
<td bgcolor="cyan">align="center">PHY</td>
<td bgcolor="cyan">align="center">CHE</td>
</tr>
<tr>
<td align="center">10-12</td>
<td bgcolor="cyan">align="center">GER</td>
<td bgcolor="cyan">align="center">FREE SLOT</td>
<td bgcolor="cyan">align="center">FWAD</td>
<td bgcolor="cyan">align="center">FWAD</td>
<td bgcolor="cyan">align="center">PHY</td>
</tr>

<tr>
<td align="center">12-1</td>
<td bgcolor="cyan">colspan="5" align ="center">LUNCH</td>

</tr>
<tr>
<td align="center">1-3</td>
<td bgcolor="cyan">colspan ="2"align="center">FREE SLOT</td>
<td bgcolor="cyan">align="center">MAT</td>
<td bgcolor="cyan">align="center">MAT</td>
<td bgcolor="cyan">align="center">SS</td>
</tr>
<tr>
<td align="center">3-5</td>
<td bgcolor="cyan">colspan ="2"align="center">FREE SLOT</td>
<td bgcolor="cyan">align="center">GER</td>
<td bgcolor="cyan">align="center">CHE</td>
<td bgcolor="cyan">align="center">FWAD</td>

</tr>
</table>
</body>
</html>
```

## OUTPUT


## HTML VALIDATOR


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
