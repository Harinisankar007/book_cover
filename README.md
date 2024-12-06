# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
    <style>
        .book-cover {
            width: 400px;
            height: 700px;
            border: 10px solid black;
            background-color: #f4f4f4;
            background-image: url(grave.avif);
            background-size: cover;
            background-position: center;
            padding: 30px;
            font-family: Arial, sans-serif;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .book-title {
            font-size: 30px;
            font-style: italic;
            font-weight: bold;
            text-align: center;
            margin-top: 50px;
        }
        .author-name {
            font-size: 18px;
            font-style: oblique;
            text-align: center;
            margin-top: 10px;
            color:white;
        }
        .book-cover img {
            display: block;
            margin: 30px auto;
            width: 100%;
        }
    </style>
</head>
<body>
    <center>
     
    <div class="book-cover">
        <hr>
        <hr>
        <div class="book-title">THE FOGGY GRAVEYARD</div>
        <bold>
        <hr>
        <hr>
        <p>"The fog creeps in, shrouding the dead in mystery,and living in dread",foggy graveyards hide secret but the misty veil also reveals the truth those who dare to listen "GONE BUT NOT FORGOTTEN"</p> 
        <h2>-HANNI PARK</h2>
        </bold>
    </center>
    </div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2024-12-07 015431.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
