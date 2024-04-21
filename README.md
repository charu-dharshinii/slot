# Ex03 Time Table
## Date: 28/02/24

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: #EFD4F7;
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: #C21460;
        }
        .c1{
            background-color: #C21460;
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - Charudharshini K(212221220008)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <td>Logic and Combinatorics</td>
            <td>Ethical Hacking Techniques</td>
            <td>Fundamentals of Web Applications Development</td>
            <td>Logic and Combinatorics</td>
            <td>Analog and Digital Communication</td>
            <td>-</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <td>-</td>
            <td>Fundamentals of Web Application Development</td>
            <td>Analog and Digital Communication</td>
            <td>Employment Enhancement Skills</td>
            <td>-</td>
            <td>-</td>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>Fundamentals of Web Application Development</td>
            <td>Open Source Operating System</td>
            <td>Artificial Intelligence</td>
            <td>Open Source Operating System</td>
            <td>Analog and Digital Communication(1 to 2)</td>
            <td>Ethical Hacking Techniques</td>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <td>Artificial Intelligence</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS417</td>
            <td>Ethical Hacking Techniques</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS545</td>
            <td>Open Source Operating System</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19MA206</td>
            <td>Logic and Combinatorics</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS413</td>
            <td>Artificial Intelligence</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY705</td>
            <td>Employment Enhancement skills (EMP)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EC306</td>
            <td>Analog and Digital Communication</td>
        </tr>
    </table>
</body>
</html>
```
## OUTPUT
![op2](https://github.com/charu-dharshinii/slot/assets/130828943/418d0330-ad4f-4818-bbfd-f81f5c0228c4)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
