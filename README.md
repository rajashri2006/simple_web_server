# EX01 Developing a Simple Webserver

# Date:01-12-2024
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
<!DOCTYPE html>

<html lang="en">
  
<head>
  
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>properties</title>
    <style>
        *{
            background-color: rgb(85, 110, 184);
        }
        table {
            width: 50%;
            border-collapse: collapse;
            margin: 80px 0;
            align-items: center;
           
        }
        th, td {
            border: 1px solid #1c211f;
            padding: 8px;
            text-align: center;
            font-size: 30px;
        }
        th {
            background-color: #5e645e;
        }
        .head{
            text-align: center;
            font-size: 50px;
            
        }

           
            
        
        
    </style>
    
</head> 

<body>
  
    <div class="head">
        <b>DEVICE PROPERTIES</b>
    </div>
    <center>
    <table style="border: 5px;">
        <tr>
            <th>DEVICE NAME</th>
            <td>ROSE</td>
        </tr>
        <tr>
            <th>PROCESSOR</th>
            <td>12th Gen Intel(R) Core(TM) i7-1255U   1.70 GHz</td>
        </tr>
        <tr>
            <th>Installed RAM</th>
            <td>16.0 GB (15.7 GB usable)</td>
        </tr>
        <tr>
            <th>DEVICES ID</th>
            <td>31A18F75-5BEE-46A4-9687-8A3402363495</td>
        </tr>
        <tr>
            <th>PRODUCT ID</th>
            <td>00342-42680-24966-AAOEM</td>
        </tr>
        <tr>
            <tr>
                <th>SYSTEM TYPE</th>
                <td>64-bit operating system, x64-based processor</td>
        </tr>
        <tr>
            <th>PEN AND TOUCH</th>
            <td>No pen or touch input is available for this display</td>
        </tr>                            
    </table>
</center>


</body>

</html>

# OUTPUT:
![Screenshot 2024-12-01 220650](https://github.com/user-attachments/assets/1f6e9a97-0646-4255-907f-971e670687c8)

# RESULT:
The program for implementing simple webserver is executed successfully.
