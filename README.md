# Ex08 CAMU Schedule using Bootstrap
## Date:31/06/2026

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS:
### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Add the Bootstrap CDN link inside the <head> section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <title>CAMU Schedule</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

    <!-- jQuery -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

    <!-- Bootstrap JS -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

    <style>
        body{
            background-color:#f5f5f5;
        }
        h1{
            text-align:center;
            color:#003366;
            margin-bottom:20px;
        }
        .table{
            background-color:white;
        }
    </style>
</head>

<body>

<div class="container">

    <h1>CAMU Schedule</h1>

    <div class="table-responsive">

        <table class="table table-bordered table-striped table-hover text-center">

            <thead class="bg-primary">
                <tr>
                    <th>Day</th>
                    <th>Period 1<br>8:00-9:00</th>
                    <th>Period 2<br>9:00-10:00</th>
                    <th>Period 3<br>10:15-11:15</th>
                    <th>Period 4<br>11:15-12:15</th>
                    <th>Period 5<br>1:00-2:00</th>
                    <th>Period 6<br>2:00-3:00</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>Monday</td>
                    <td>Python</td>
                    <td>Maths</td>
                    <td>DBMS</td>
                    <td>DBMS Lab</td>
                    <td>DBMS Lab</td>
                    <td>English</td>
                </tr>

                <tr>
                    <td>Tuesday</td>
                    <td>AI</td>
                    <td>Python</td>
                    <td>Maths</td>
                    <td>English</td>
                    <td>Web Tech</td>
                    <td>Web Tech</td>
                </tr>

                <tr>
                    <td>Wednesday</td>
                    <td>Maths</td>
                    <td>AI</td>
                    <td>Python</td>
                    <td>English</td>
                    <td>DBMS</td>
                    <td>Sports</td>
                </tr>

                <tr>
                    <td>Thursday</td>
                    <td>Web Tech</td>
                    <td>Maths</td>
                    <td>AI</td>
                    <td>Python</td>
                    <td>DBMS Lab</td>
                    <td>DBMS Lab</td>
                </tr>

                <tr>
                    <td>Friday</td>
                    <td>English</td>
                    <td>Web Tech</td>
                    <td>Maths</td>
                    <td>AI</td>
                    <td>Python Lab</td>
                    <td>Python Lab</td>
                </tr>

                <tr>
                    <td>Saturday</td>
                    <td>Library</td>
                    <td>Seminar</td>
                    <td>Project</td>
                    <td>Project</td>
                    <td>Counselling</td>
                    <td>Sports</td>
                </tr>
            </tbody>

        </table>

    </div>

</div>

</body>
</html>
```


## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2026-05-31 121826" src="https://github.com/user-attachments/assets/15dedf86-71c6-4a5a-9861-1625b70e6d78" />


## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
