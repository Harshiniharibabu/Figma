# Ex09 Event Registration Web Application
## Date:27/05/2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
## Frame 1(html):
````
<!DOCTYPE html>
<html>
<head>
    <title>Login Page</title>

    <style>

        body{
            margin:0;
            font-family:Arial, Helvetica, sans-serif;
            background:white;
        }

        .container{
            width:350px;
            height:750px;
            margin:20px auto;
            background:url(image.png);
            border-radius:30px;
            text-align:center;
            padding-top:30px;
        }

        .logo{
            width:180px;
            margin-top:20px;
        }

        h2{
            margin-top:30px;
        }

        .form{
            margin-top:120px;
        }

        label{
            display:block;
            margin-top:20px;
            font-weight:bold;
        }

        input{
            width:170px;
            height:28px;
            border:none;
            border-radius:20px;
            background:gray;
        }

    </style>
</head>

<body>

<div class="container">

    <img src="logo.png" class="logo">

    <h2>LOGIN</h2>

    <div class="form">

        <label>EMAIL ID :</label>
        <input type="text">
        <label>PASSWORD :</label>
        <input type="password">
    </div>
</div>
</body>
</html>
````
## Frame2:
````
<!DOCTYPE html>
<html>
<head>
    <title>Events Page</title>

    <style>

        body{
            margin:0;
            font-family:Arial, Helvetica, sans-serif;
        }

        .container{
            width:350px;
            height:750px;
            margin:20px auto;
            background:url(image.png);
            border-radius:30px;
            padding:20px;
        }

        .top{
            width:250px; 
            display:block;
            margin:auto;
        }

        h2{
            text-align:center;
            margin-top:20px;
        }

        ul{
            margin-top:40px;
            line-height:40px;
            font-size:18px;
        }

        .click{
            text-align:center;
            margin-top:30px;
        }

        
    </style>
</head>

<body>

<div class="container">
    <h2> EVENTS</h2>

    <ul>
        <li>AI Revolution Summit</li>
        <li>Cyber Security Arena</li>
        <li>Robotics Expo</li>
        <li>AR/VR Experience Zone</li>
        <li>Gaming & Esports Battle</li>
        <li>Drone Tech Championship</li>
    </ul>

</div>

</body>
</html>
````
## Frame3:
```
<!DOCTYPE html>
<html>
<head>
    <title> Details</title>

    <style>

        body{
            margin:0;
            background:#111;
            font-family:Arial, Helvetica, sans-serif;
        }

        .container{
            width:350px;
            height:820px;
            margin:20px auto;
            background:linear-gradient(to bottom,#dfe7f5,#173f88);
            border-radius:30px;
            padding:20px;
        }
        .top{
            width:250px;
            display:block;
            margin:auto;
        }

        h2{
            text-align:center;
            margin-top:20px;
        }

        form{
            margin-top:30px;
        }

        label{
            display:block;
            margin-top:15px;
            font-weight:bold;
        }

        input[type=text],
        input[type=email]{
            width:220px;
            height:28px;
            border:none;
            border-radius:20px;
        }

        h3{
            text-align:center;
            margin-top:30px;
        }

        button{
            display:block;
            margin:40px auto;
            width:180px;
            height:45px;
            border:none;
            border-radius:25px;
            background:orangered;
            color:black;
            font-size:16px;
        }

        .submit{
            text-align:center;
            color:red;
            font-weight:bold;
        }

    </style>
</head>

<body>

<div class="container">

    <img src="college.png" class="top">

    <h2>EVENT REGISTRATION FORM</FORM></h2>

    <form>

        <label>Full Name</label>
        <input type="text">
        <label>Register Number</label>
        <input type="text">
        <label>Intrested in</label>
        <input type="text">
        <label>Mobile Number</label>
        <input type="text">
        <button>submit</button>

        </form>
</div>

</body>
</html>
```
## Frame4:
````
<!DOCTYPE html>
<html>
<head>
    <title>Final Page</title>

    <style>

        body{
            margin:0;
            background:#111;
            font-family:Arial, Helvetica, sans-serif;
        }

        .container{
            width:350px;
            height:780px;
            margin:20px auto;
            background:linear-gradient(to bottom,#dfe7f5,#0b3f91);
            border-radius:30px;
            text-align:center;
            padding-top:20px;
        }

        .top{
            width:250px;
        }

        h2{
            margin-top:20px;
        }

        .circle{
            width:180px;
            height:180px;
            background:#7bdc34;
            border-radius:50%;
            margin:40px auto;
            line-height:180px;
            font-size:80px;
            color:white;
        }

        .msg{
            font-size:18px;
        }

        .msg2{
            width:280px;
            margin:auto;
            margin-top:30px;
            line-height:30px;
        }

        .map{
            width:180px;
            border-radius:20px;
            margin-top:30px;
        }
        span{
            color:white;
            font-weight:bold;
        }

    </style>
</head>

<body>

<div class="container">

    <img src="college.png" class="top">

    <h2>REGISTRATION SUCCESSFUL</h2>

    <div class="circle">
        ✔
    </div>

    <p class="msg">Thank You!!</p>
</div>

</body>
</html>
````


## OUTPUT:
![alt text](<Screenshot 2026-05-27 232837.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
