# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Book Cover</title>
        <style>
            *{
                font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            }
            body {
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh; 
                margin: 0; 
                background-color:lightgray;
            }

        .cover{
            display: flex;
            height: 98vh;
            width: 50%;    
            justify-content: center;
            align-items: center;
            border-color: black;
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
            overflow: hidden;
            background-image: url(danush.jpg);
            background-repeat: no-repeat;
        }
        
        .title{
            position: absolute;
            color:rgb(253, 247, 247);
            top: 150px;
            font-size: 18px;
        }

        .text1{
            position: absolute;
            color: darkcyan;
            top: 15px;
            left: 560px;
        }

        .line1{
            position: absolute;
            top: 60px;
            left: 540px;
        }

        .edition{
            position:absolute;
            top: 550px;
            left: 560px;
            color:skyblue;
        }

        .line2{
            position: absolute;
            top: 600px;
            left: 540px;
        }

        .author{
            position: absolute;
            top: 610px;
            left: 560px;
            color:coral;
        }

        .image img{
            height: 100px;
            width: 80px;
            position: absolute;
            top: 560px;
            left: 900px;
        }
                
    </style>
    </head>
    <body>
        <div class="cover">
            <div class="title">
                <h1>THE HAPPY DEVELOPER</h1>
                <h5>The Happy Developer's Guide to Creating, Innovating, and Thriving in Software Development.</h5>
            </div>
            <div class="text1">
                <h3>CODING</h3>
            </div>
            <hr class="line1" width="210px">
            <div class="edition">
                <h3>FIRST EDITION</h3>
            </div>
            <div class="author">
                <h3>DANUSH S</h3>
            </div>
            <hr class="line2" width="170px">
            <div class="image">
                <img src="profile_pic.png">
            </div>
        </div>
    </body>
    </html>


## OUTPUT:
![Screenshot (450)](https://github.com/danush564/cover/assets/98585166/f1fc9a36-9283-4684-ba7f-3cc78cc82fc2)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
