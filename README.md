# Ex03 Time Table
# Date:28/09/2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Time Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: whitesmoke;
            margin: 0;
            padding: 20px;
            text-align: center;
            color: black;
        }

        h1 {
            margin-bottom: 70px;
        }

        table {
            margin: 0 auto;
            width: 90%;
            max-width: 1000px;
            border-collapse: collapse;
            background-color: #ffffff;
            color: #000000;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            border-radius: 10px;
            overflow: hidden;
            border: 4px double #4CAF50; /* Double outer border */
        }

        th, td {
            padding: 12px;
            border: 2px double black; /* Double inner borders */
            font-size: 16px;
        }

        th {
            background-color: plum;
            color: black;
        }

        /* Make the first column (days) bold */
        td:first-child {
            font-weight: bold;
        }

        tr:nth-child(even) td {
            background-color: pink;
        }

        tr:nth-child(odd) td {
            background-color: palevioletred;
        }

        tr:hover td {
            background-color: #d1ffd1;
        }

        @media screen and (max-width: 600px) {
            th, td {
                font-size: 12px;
                padding: 8px;
            }
        }
    </style>
</head>
<body>
    <h1>My Time Table</h1>
    <table>
        <tr>
            <th>Day</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>12-1</th>
            <th>1-3</th>
            <th>3-5</th>
        </tr>

        <tr>
            <td>Monday</td>
            <td>Free</td>
            <td>Web</td>
            <td>Lunch</td>
            <td>C Programming</td>
            <td>Free</td>
        </tr>

        <tr>
            <td>Tuesday</td>
            <td>Web</td>
            <td>Free</td>
            <td>Lunch</td>
            <td>C Programming</td>
            <td>Free</td>
        </tr>

        <tr>
            <td>Wednesday</td>
            <td>Free</td>
            <td>Free</td>
            <td>Lunch</td>
            <td>Mentor Meet</td>
            <td>C Programming</td>
        </tr>

        <tr>
            <td>Thursday</td>
            <td>Free</td>
            <td>C Programming</td>
            <td>Lunch</td>
            <td>Free</td>
            <td>C Programming</td>
        </tr>

        <tr>
            <td>Friday</td>
            <td>Web</td>
            <td>Free</td>
            <td>Lunch</td>
            <td>C Programming</td>
            <td>Free</td>
        </tr>

        <tr>
            <td>Saturday</td>
            <td>Web</td>
            <td>Free</td>
            <td>Lunch</td>
            <td>Free</td>
            <td>Free</td>
        </tr>
    </table>
</body>
</html>
```
# OUTPUT
<img width="1565" height="757" alt="image" src="https://github.com/user-attachments/assets/027ad078-754a-4220-9001-a012dd8cbe08" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
