# EX 06 Book Cover Page Design
## Date: 16.11.2025
## Developed by :KARTHICK V
## Register No. : 212223040086
## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover</title>

    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body{
            background: #111;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, Helvetica, sans-serif;
        }

        .cover{
            position: relative;
            width: 550px;
            height: 800px;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.6);
        }

        .cover img.bg{
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: brightness(0.45); 
        }

        .title-block{
            position: absolute;
            top: 120px;
            left: 40px;
            color: white;
        }

        .title-block h1{
            font-size: 48px;
            line-height: 1.1;
            font-weight: 800;
            text-transform: uppercase;
        }

        .title-block p{
            margin-top: 10px;
            font-size: 20px;
            opacity: 0.9;
        }

        .edition{
            position: absolute;
            bottom: 150px;
            left: 40px;
            color: rgb(16, 219, 212);
            font-size: 24px;
            font-weight: bold;
        }

        .edition hr{
            margin-top: 8px;
            width: 180px;
            border: none;
            border-top: 2px solid rgb(16, 219, 212);
        }

        .author{
            position: absolute;
            bottom: 80px;
            left: 40px;
            font-size: 28px;
            color: white;
            font-weight: bold;
        }

        .character{
            position: absolute;
            bottom: 40px;
            right: 30px;
            width: 180px;
            height: 250px;
        }

        .character img{
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
    </style>
</head>

<body>

    <div class="cover">
        <img src="bg.png" class="bg">
        <div class="title-block">
            <h1>Ninja<br>Coder</h1>
            <p>Your Ultimate Coding Guide<br>Python - C - C# - C++ - Java<br>ALL IN ONE !!!!</p>
        </div>
        <div class="edition">
            FIRST EDITION
            <hr>
        </div>
        <div class="author">Akash Ganesan</div>
        <div class="character">
            <img src="1.png">
        </div>

    </div>

</body>
</html>

```

## OUTPUT:

<img width="700" height="976" alt="image" src="https://github.com/user-attachments/assets/2a743b90-f4e4-427b-bd9b-f56ce3f6d17b" />


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.

---
