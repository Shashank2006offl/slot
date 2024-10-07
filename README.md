# Ex03 Time Table
## Date:01-10-2024

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
<html>
<head>
<title >Slot Time Table - SHASHANK R (23013949)</title>
<style>

table {
  border-collapse: collapse;
  width: 100%;
}

th{
  text-align: center;
  padding: 8px;
  border: 1px solid #ddd;
}
td {
    text-align: LEFT;
    padding: 8px;
    border: 1px solid #ddd;
}
tr:nth-child(even) {
  background-color: #7bf1f5;
}
th {
    background-color: #f8a0d0;
  }
td:nth-child(1) {
    background-color: #a5b6f1;
}

tr:nth-child(ODD) {
    background-color: #25d1e1;
  }
</style>
</head>
<body>

<h2 text-align="center">Slot Time Table -SHASHANK R (23013949)</h2>

<table>
  <tr>
    <th>Day/Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
  </tr>
  <tr>
    <td>8-10</td>
    <td>COMPUTER ARCHITECTURE</td>
    <td>SOFTWARE ENGINEERING</td>
    <td>FREE SLOT</td>
    <td>INTRO TO ML</td>
    <td>FREE SLOT</td>
  </tr>
  <tr>
    <td>10-12</td>
    <td>FREE SLOT</td>
    <td>OPERATING SYSTEM</td>
    <td>FWAD</td>
    <td>DATA SCIENCE</td>
    <td>DATA SCIENCE</td>
  </tr>
  <tr>
    <td>12-1</td>
    <td><b>L</b></td>
    <td><b>U</b></td>
    <td><b>N</b></td>
    <td><b>C</b></td>
    <td><b>H</b></td>
    
  </tr>
  <tr>
    <td>1-3</td>
    <td>TNTRO TO ML</td>
    <td>QA-1</td>
    <td>WEB APPLICATION</td>
    <td>OPERATING SYSTEM</td>
    <td>FREE SLOT</td>
  </tr>
  <tr>
    <td>3-5</td>
    <td>WEB APPLICATION</td>
    <td>ADVANCED C PROGRAM</td>
    <td>COMPUTER ARCHITECTURE</td>
    <td>SOFTWARE ENGINEERING</td>
    <td>COMPUTER ARCHITECTURE</td>
  </tr>
</table>

</body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/2b6ec5db-4a04-4035-b05c-0329b8882f2f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
