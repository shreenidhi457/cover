# Ex.06 Book Front Cover Page Design
## Date:19-12-2025
## Ref no:25012095

## AIM:
To design a book front cover page using HTML and CSS.

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Web Development Book Cover</title>

    <style>
        body {
            background: #ffffff;
            font-family: "Courier New", monospace;
            margin: 0;
            padding: 40px;
            display: flex;
            justify-content: center;
        }

        .cover {
            width: 420px;
            height: 650px;
            background: linear-gradient(to bottom right, #04332c, #22776c, #53b5a8);
            color: white;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0,0,0,0.2);
            padding: 30px;
            position: relative;
        }

        .header-text {
            font-size: 18px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .title {
            margin-top: 80px;
            font-size: 38px;
            font-weight: bold;
            text-align: left;
            line-height: 48px;
        }

        .subtitle {
            margin-top: 20px;
            font-size: 20px;
        }

        .author-section {
            position: absolute;
            bottom: 40px;
            left: 30px;
            right: 30px;
        }

        .edition-text {
            font-size: 20px;
            font-weight: bold;
            color: #000;
            margin-bottom: 10px;
        }

        .author-photo {
            float: right;
            width: 110px;
            height: 140px;
            border: 3px solid white;
            object-fit: cover;
        }

        .author-name {
            margin-top: 10px;
            font-size: 18px;
            font-weight: bold;
            color: #000;
        }

        .publisher {
            margin-top: 10px;
            font-size: 20px;
            font-weight: bold;
            color: white;
        }

        hr {
            border: 1px solid white;
            margin-top: 8px;
        }
    </style>

</head>
<body>

<div class="cover">

    <div class="header-text">SEC INSIGHT</div>

    <hr>

    <div class="title">
        MAGIC:<br>
        Unseen Worlds Uncovered<br>
        Reference
    </div>

    <div class="subtitle">
        Unveiling the Unseen Dimensions
    </div>

    <div class="author-section">

        <img src="/static/photo.png" class="author-photo" alt="Author">

        <div class="edition-text">Extended Edition</div>

        <hr>

        <div class="author-name">Shreenidhi S</div>

        <div class="publisher">SEC</div>

    </div>

</div>

</body>
</html>
~~~

## OUTPUT:

![output](https://github.com/user-attachments/assets/5f3f8dda-e43b-4e61-ab7f-c657f8ceeaad)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
