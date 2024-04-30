# Ex.06 Book Front Cover Page Design
## Date:30/4/24

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
<html>
<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color:rgb(255, 255, 255);
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color:rgb(74, 49, 203);
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      margin: 50px auto;
      position: relative;
    }
    
    .book-cover .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 24px;
      font-weight: bold;
      color: rgb(240, 251, 255);
    }
    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 10px;
      width: 80px;
    }
    .book-cover .title1 {
      position: absolute;
      top: 80px;
      left: 50px;
      font-size: 40px;
      font-weight: bold;
      color:  rgb(18, 219, 68);
    }
    .book-cover .title2 {
      position: absolute;
      top: 130px;
      left: 30px;
      font-size: 40px;
      font-weight: bold;
      color:  
      
      
      
      rgba(220, 20, 20, 0.723);
    }

    .book-cover .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color:  rgb(213, 39, 190);
    }
    .book-cover .subtitle2 {
      position: absolute;
      top: 500px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: rgb(164, 20, 73);
    }
    .book-cover .subtitle3 {
      position: absolute;
      top: 530px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: white;
    }
    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }
    .book-cover .line3
    {
      position: absolute;
      bottom:38px;
      left: 20px;
      width: 115px;
    }


    .book-cover .author {
      position: absolute;
      bottom: 25px;
      left: 20px;
      font-size: 18px;
      color: whitesmoke;
    }

    .book-cover .number {
      position: absolute;
      bottom: 5px;
      left: 20px;
      font-size: 18px;
      color: white;
    }

    .book-cover .end {
      position: absolute;
      bottom: 5px;
      right: 50px;
      font-size: 18px;
      color: white;
    }
    .book-cover .mypic
    {
      position: relative;
      top:550px;
      left: 370px;
      width : 8px;
      height: 8px;
      background-size:fit;
    }


    .book-cover .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="harry.jpg" alt="Book Cover Image" class="image">
    <div class="insight">harry potter the mystery dungeon</div>
    <div class="line1"><hr style="color:blanchedalmond"></div>
    <div class="title2"> deadly hollows and witches </div>
    <div class="subtitle1">Look deep into nature, and then you will understand everything betterWeak minds sink under prosperity as well as adversity; but strong and deep ones have two high tides. .... ...</div>
   >
    <div class="line3"><hr style="color:blanchedalmond"></div>
    <div class="mypic"><img src="WhatsApp Image 2024-04-12 at web.jpg"width="120" height="120" ></div>
    <div class="end">SEC</div>
    <div class="number">212221040155</div>
    <div class="author">sivaragul.m</div>
</div>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2024-04-30 143037.png>)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
