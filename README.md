# Ex.06 Book Front Cover Page Design
# Date:20/11/2024
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

<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GAME OF THRONE</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

        .book-cover {
            width: 400px;
            height: 600px;
            background-image: url("C:\\Users\\Arun\\Documents\\125876-1080x1920-phone-full-hd-game-of-thrones-wallpaper.jpg");

            background-size: cover;
            background-position: center;
            border-radius: 15px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.5);
            position: relative;
            overflow: hidden;
        }

        .book-title {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            color: white;
            font-family: 'Georgia', serif;
            font-size: 36px;
            font-weight: bold;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.7);
        }

        .subtitle {
            position: absolute;
            bottom: 80px;
            left: 50%;
            transform: translateX(-50%);
            color: white;
            font-family: 'Arial', sans-serif;
            font-size: 18px;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="book-title">MOTHER OF DRAGON</div>
        
    </div>

</body>
</html>

# OUTPUT:

![Screenshot (2)](https://github.com/user-attachments/assets/63dab545-95b6-4f6a-b0f3-4f86e2271bde)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
