# Ex03 Time Table
## Date:20.09.2025

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
    <head>
        <title>timetable</title>
    </head>
    <body>
        <center>
            <img src="logo.png" width="1100" height="200"><br>
            <h1>Slot Time Table- Jagan kumar(25012671)</h1>
        </center>
        <center>
        <table border="3" cellspacing="5" cellspadding="10" height="200">
            <tr bgcolor="sky blue">
                <th>Day/time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="green">
                <td bgcolor="sky blue">8-10</td>
                <td>Eng</td>
                <td>Free slot</td>
                <td>Web</td>
                <td>Eng</td>
                <td>Pyt</td>
                <td>Web</td>
            </tr>
            <tr bgcolor="green">
                <td bgcolor="sky blue">10-12</td>
                <td>Free slot</td>
                <td>Pyt</td>
                <td>Web</td>
                <td>Free slot</td>
                <td>pyt</td>
                <td>pyt</td>
            </tr>
            <tr bgcolor="green">
                <td bgcolor="sky blue">12-1</td>
                <td colspan="6">Lunch Break</td>
            </tr>
            <tr bgcolor="green">
                <td bgcolor="sky blue">1-3</td>
                <td>Eng</td>
                <td>Eng</td>
                <td>Mentor meet</td>
                <td>Eng</td>
                <td>Web</td>
                <td>Web</td>
            </tr>
            <tr bgcolor="green">
                <td bgcolor="sky blue">3-5</td>
                <td colspan="2">Free slot</td>
                <td>python</td>
                <td>Free slot</td>
                <td>Eng</td>
                <td>Free slot</td>
            </tr>
        </table><br><br>
        <table border="3" callspacing="3" cellsapdding="10" height="200">
            <tr bgcolor="sky blue">
                <th>S.no.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            
        <tr bgcolor="green">
                <td bgcolor="sky blue">1</td>
                <td>19AI414</td>
                <td>Fundamental of Web appilication(web)</td>
            </tr>
            <tr bgcolor="green">
                <td bgcolor="sky blue">2</td>
                <td>19AI301</td>
                <td>Python(pyt)</td>
            </tr>
            <tr bgcolor=" green">
                <td bgcolor="sky blue">3</td>
                <td>19EN101</td>
                <td>Communicative English(Eng)</td>
            </tr>
            </table>
        </center>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-09-24 094848.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
