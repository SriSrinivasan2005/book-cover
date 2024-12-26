# Ex.06 Book Front Cover Page Design
## Date:15-12-2024

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
<html lang="en"> 
    <head>
        <style>
            body{
                
                display: flex;
                align-items: center;
                justify-content: center;
                height: 100vh;
                font-family: Arial, sans-serif;
                background-color: aliceblue;

            }

            .book-cover{
                background: url('HTML.jpg') no-repeat center / cover;
                text-align: center;
                padding: 20px;
                border: 2px;
                height: 600px;
                width: 400px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            }        
            .book-title h1{
                color: rgb(241, 15, 15);
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                font-size: 20;
                position: absolute;
                right: 39%;
                bottom: 76%;

            }
            .book-tagline{
                color: beige;
                text-align: center;
                font-style: italic;
                font-family: 'Times New Roman', Times, serif;
                font-size: 70%;
                position: absolute;
                top: 25%;
                left: 38%;
            }
            .book-author h3{
                font-size: 20;
                font-style: italic;
                font-family: cursive;
                color: gainsboro;
                align-items: center;
            }
            .book-author{
                text-align: end;
                font-weight: 400px;
                place-items: end;
                position: absolute;
                bottom: 10%;
                right: 40%;
            }


        </style>
    </head>
    <body>
        <div class="book-cover">
            <div class="book-title">
              <h1>WEB APPLICATION DEVELOPMENT</h1>
            </div>  
            <div class="book-tagline">
                <h2>"CODE YOUR VISION,POWER YOUR FUTURE"</h2>
            </div>
            <div class="book-author">
                <img src="srini.jpg" height="100px" width="100px">
                <h3>SRI SRINIVASAN.K</h3>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:

![alt text](<book cover.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
