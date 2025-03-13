# Ex03 Time Table
## Date: 13/3/2025

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
### DHANAAAKHAASH S.T (212224240032)
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center><table border="5">
        <caption>SLOT TIME TABLE</caption>
        <tr style="background-color: red;">
            <th> Day/time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
         <tr style="background-color:red;">

            <td>8-10</td>
            <td colspan="3">Free Slot</th>
            <td>phy</td>
            <td>che</td>
        </tr>
        <tr style="background-color: yellow;">
            <td>10-12</td>
            <td>FRE</td>
            <td>free slot</td>
            <td colspan="2">FWAD</td>
            <td>PHY</td>
        </tr>
        <tr style="background-color: yellow;">
            <td>12-1</td>
            <td colspan="5">FREE SLOT</td>
        </tr>
        <tr style="background-color: red;">
            <td>1-3</td>
            <td colspan="2">FREE SLOT</td>
            <td>MATH</td>
            <td>EVS</td>
            <td>CHEM</td>
        </tr>
        <tr style="background-color:red;">
            <td>3-5</td>
            <td rowspan="2">FREE SLOT</td>
            <td>FRE</td>
            <td>FRE</td>
            <td>CHE</td>
            <td>FWAD</td>
            
        </tr>

    </table></center>
    <hr>
    <center><table border="2">
        <tr style="background-color: blue;">
            <td>s.no</td>
            <td>subject code </td>
            <td>subject name</td>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI304</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <td>2</td>
            <td>SH0721</td>
            <td>FRE</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19CY205</td>
            <td>CHEM</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19PY401</td>
            <td>PHY</td>
        </tr>
        <tr>
            <td>5</td>
            <td>EVS206</td>
            <td>EVS</td>
        </tr>
</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/4bfab6ae-aa41-4568-a775-716280fe7a68)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
