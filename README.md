# Ex03 Time Table
## Date:26-04-2025

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
'''

<!DOCTYPE html>

<html lang="en">
    
<head>
    
<meta charset="UTF-8">

<title>Slot Timetable - Harini</title>

<style>
    
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
        }
        table {
            border-collapse: collapse;
            width: 90%;
            margin: 20px auto;
        }
        th, td {
            border: 2px solid #000;
            padding: 12px;
            text-align: center;
        }
        th {
            background-color: #ffb6c1;
        }
        td {
            background-color: #e0ffff;
        }
        caption {
            font-size: 24px;
            margin-bottom: 10px;
            font-weight: bold;
        }
        img {
            display: block;
            margin: 20px auto;
        }
    
</style>

</head>

<body>

<center>
<img src="logo.png" height="100" width="540" alt="College Logo">
</center>

<table>
<caption>SLOT TIMETABLE - HARINI.S (212224230083)</caption>
<tr>
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
</tr>
<tr>
        <th>8-9 AM</th>
        <td>19MA222</td>
        <td>19AI305</td>
        <td>19AI403</td>
        <td>19AI414</td>
        <td>19AI410</td>
        <td rowspan="5" style="background-color: #ffe4b5;">Module Completion</td>
</tr>
<tr>
        <th>9-10 AM</th>
        <td>19AI410</td>
        <td>19AI301C</td>
        <td>19EY710</td>
        <td>19MA222</td>
        <td>19AI305</td>
</tr>
<tr>
        <th>10-11 AM</th>
        <td>19AI301C</td>
        <td>19EY709</td>
        <td>19AI414</td>
        <td>19AI403</td>
        <td>19EY710</td>
</tr>
<tr>
        <th>11-12 PM</th>
        <td>19AI403</td>
        <td>19AI305</td>
        <td>19MA222</td>
        <td>19EY709</td>
        <td>19AI301C</td>
</tr>
<tr>
        <th>12-1 PM</th>
        <td colspan="5" style="background-color: #ffa07a;">Lunch Break</td>
</tr>
<tr>
        <th>1-2 PM</th>
        <td>19EY709</td>
        <td>19AI410</td>
        <td>19AI305</td>
        <td>19AI403</td>
        <td>19MA222</td>
        <td style="background-color: #ffe4b5;">Sessional Prep</td>
</tr>
<tr>
        <th>2-3 PM</th>
        <td>19AI414</td>
        <td>19EY710</td>
        <td>19AI301C</td>
        <td>19AI410</td>
        <td>19AI414</td>
        <td style="background-color: #ffe4b5;">Sessional Prep</td>
</tr>
</table>

<!-- Subject Codes Table -->
<table border="2" style="margin-top: 30px; width: 60%; margin-left: auto; margin-right: auto;">
<caption><b>Subject Details</b></caption>
<tr>
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
</tr>
<tr>
        <td>1</td>
        <td>19MA222</td>
        <td>Probability and Queueing Models</td>
</tr>
<tr>
        <td>2</td>
        <td>19AI305</td>
        <td>Advanced C Programming</td>
</tr>
<tr>
        <td>3</td>
        <td>19AI403</td>
        <td>Introduction to Data Science</td>
</tr>
<tr>
        <td>4</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
</tr>
<tr>
        <td>5</td>
        <td>19AI410</td>
        <td>Introduction to Machine Learning</td>
</tr>
<tr>
        <td>6</td>
        <td>19AI301C</td>
        <td>Python and Linear Algebra</td>
</tr>
<tr>
        <td>7</td>
        <td>19EY710</td>
        <td>Quantitative Ability</td>
</tr>
<tr>
        <td>8</td>
        <td>19EY709</td>
        <td>Reasoning Ability</td>
</tr>
</table>

</body>
</html>
'''

## OUTPUT
![alt text](<Screenshot 2025-04-26 183624.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
