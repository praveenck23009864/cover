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
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(0, 140, 255);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(football.png);
            background-size: cover;
        }
        .insight{
            color: rgb(0, 149, 255);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color: rgb(0, 132, 255);
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 24px;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(0, 60, 255);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">EXPERT INSIGHT</div>
            <div class="hrstyle"><hr style="color: rgb(0, 234, 255);"></div>
            <div class="booktitle"><h1>Cristiano Ronaldo: The Way i Feel</h1></div>
            <div class="subtitle">story of Cristiano Ronaldo</div>
            <div class="mypic"><img src="my image.jpg" width="130" height="145" alt=""></div>
            <div class="id"><hr style="color: rgb(162, 63, 139);"></div>
            <div class="author"><p><b>BY praveen ck</b></p></div>
            <div class="pub">OPEN >>></div>
            <div class="ed"><b>vol-1</b></div>
        </div>
    </bodY>
</html>
```
## OUTPUT:
![Screenshot 2023-11-07 135639](https://github.com/praveenck23009864/cover/assets/141472050/e2df56e2-986c-479c-b73a-2d40e958ca0d)

![Screenshot 2023-11-07 135702](https://github.com/praveenck23009864/cover/assets/141472050/40b5d6a4-a337-48fe-9d5b-8af134e0a17c)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
