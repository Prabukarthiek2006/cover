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
        body
        {

            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .book{
            width: 480px;
            height: 740px;
            background-color:#241E20;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content:space-between;
            align-items: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            text-align: center;
            font-family:'Times New Roman', Times, serif;
        }
        .book h2 {
    font-size: 1.4rem; 
    font-family:'Times New Roman', Times, serif
    color : white;
    margin : 5px 0 0; 
    line-height: 1;
}
.book h3 {
    font-size: 20px; 
    font-family:'Times New Roman', Times, serif; 
    color: white;
    margin: 5px 0 0; 
    line-height: 1;
}
.book h4 {
    font-size: 70px; 
    font-family:'Times New Roman', Times, serif ;
    color: skyblue;
    margin: 5px 0 0; 
    line-height: 1;
}
.book h6 {
    font-size: 60px; 
    font-family:'Times New Roman', Times, serif ;
    color: skyblue;
    margin: 5px 0 0;
    line-height: 1;
}
.book h4, .book h5, .book h6 {
    margin: 0;
    line-height: 1;
}





    </style>
</head>
<body>
    <h1><ma</h1>
    <container>
        <div class="book">
        <div><h2><b>Build data driven solution using R</b></h2></div>
        <div><h4><b>DATA <br>SCINCE</b></h4></div>
        <div><h5><b>--------- for ----------</b></h5></div>
        <div><h6><b>FUNDRAISING</b></h6></div>
        <div><img src="imagebook.jpg" width="250" height="300"></div>    
        <div><h3>Written By Prabu Karthiek (24010663)</h3></div>
     </div>
    </container>
    
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2024-11-30 001124.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
