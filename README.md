# EX01 Developing a Simple Webserver
## Date: 02.04.2024

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ExtraMarks Online school</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        /* CSS styles can be included here or linked externally */

        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            margin: 0;
            padding: 0;
            background-image: url('download2.png');
            background-size: contain;
            background-position: center;
            background-attachment: fixed; /* This ensures the background image stays fixed as you scroll */
        }
    
        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #f4f4f4;
            padding: 10px;
            text-align: center;
        }
        nav a {
            text-decoration: none;
            color: #333;
            padding: 10px;
        }
        nav a:hover {
            background-color: #ddd;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Our School Online</h1>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#courses">Courses</a>
        <a href="#contact">Contact Us</a>
    </nav>



    <!--Row-->
    <div>
    <section id="Login">
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Login as</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Guest</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Staff</a>
          </li>

        </div>
        </div>
    </nav>
    </section>
    </div>
    <footer>
        <p>&copy; 2024 School Online. All rights reserved.</p>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    </body>
</html>


## OUTPUT:
![alt text](screenshot.png)

## RESULT:
The program for implementing simple webserver is executed successfully.
