# Ex.06 Book Front Cover Page Design
## Date: 07/12/2024

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
    <meta charset="UTF-8">
    <title>BOOK COVER PAGE</title>
    <link rel="stylesheet" href="book.css" type="text/css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: rgba(11, 80, 120, 0.936);
            font-family: Arial, Helvetica, sans-serif;
        }
        .book-cover {
            width: 800px;
            height: 1000px;
            background-image: url('Screenshot 2024-12-07 185136.png');
            background-repeat: no-repeat;
            background-size: cover;
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            padding: 50px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        .book-title h1 {
            font-size: 3.5rem;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 2px;
            word-spacing: 2px;
            color: rgb(8, 5, 5);
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.5);
            background-color: rgba(255, 255, 255, 0.7); /* Background color for text */
            padding: 10px; /* Padding around text */
        }
        .book-tagline h2 {
            font-size: 2.5rem;
            text-align: center;
            color: rgb(1, 0, 0);
            background-color: rgba(255, 255, 255, 0.7); /* Background color for text */
            padding: 10px; /* Padding around text */
        }
        .book-author {
            text-align: end;
            font-weight: 400;
            color: rgb(76, 19, 181);
        }
        .book-author h2 {
            font-size: 2em;
            color: rgba(0, 0, 0, 0.973);
            background-color: rgba(255, 255, 255, 0.7); /* Background color for text */
            padding: 10px; /* Padding around text */
        }
        hr {
            border: none;
            height: 1px;
            background-color: red;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="book-title">
            <hr>
            <h1><i>Math Not the Subject</i></h1>
            <hr>
        </div>
        <div class="book-tagline">
            <h2>"Math Not the Subject: Discover the Patterns that Shape Our World"</h2>
        </div>
        <div class="book-author">
            <img src="image.jpg" width="180" height="180" alt="Author's Image">
            <h2>Sudarsan.A</h2>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-10 140535.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
