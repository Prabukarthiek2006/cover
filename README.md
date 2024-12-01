# Ex.06 Book Front Cover Page Design
## Date: 30-11-2024

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        /* General Styles */
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: linear-gradient(to bottom right, #333333, #000000);
            font-family: 'Times New Roman', Times, serif;
        }

        /* Book Cover Styles */
        .book {
            width: 480px;
            height: 740px;
            background-color: #241E20;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            text-align: center;
            padding: 20px;
        }

        .book h2, .book h3, .book h4, .book h5, .book h6 {
            margin: 0;
            line-height: 1.2;
        }

        .book h2 {
            font-size: 1.4rem;
            color: #ffffff;
            margin-bottom: 10px;
        }

        .book h4 {
            font-size: 70px;
            color: skyblue;
        }

        .book h5 {
            font-size: 18px;
            color: #ffffff;
            margin: 10px 0;
        }

        .book h6 {
            font-size: 60px;
            color: skyblue;
        }

        /* Edition Box */
        .edition-box {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 10px;
            background: crimson;
            color: white;
            font-size: 24px;
            font-weight: bold;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            text-transform: uppercase;
        }

        .book h3 {
            font-size: 14px;
            color: #ffffff;
            margin-top: 15px;
            padding-top: 10px; /* Adds spacing between text and the line */
            border-top: 2px solid #ffffff; /* Line above the text */
            width: 80%; /* Adjusts line width to fit the text nicely */
            text-align: center;
        }

        .book img {
            margin: 15px 0;
            border: 3px solid #ffffff;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }

        .book img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="book">
        <h2><b>Build Data-Driven Solutions Using R</b></h2>
        <h4><b>DATA <br> SCIENCE</b></h4>
        <h5><b>--------- for ----------</b></h5>
        <h6><b>FUNDRAISING</b></h6>
        <!-- Edition Box -->
        <div class="edition-box">Edition - 3</div>
        <img src="imagebook.jpg" alt="Book Cover" width="250" height="300">
        <h3>ASHUTOSH NANDESHWAR, Ph.D | RODGER DEVINE, M.S</h3>
    </div>
</body>
</html>


```

## OUTPUT:

![alt text](<Screenshot 2024-12-01 124550.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
