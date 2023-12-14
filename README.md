# Ex.06 Book Front Cover Page Design
## Date:14/12/2023

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
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color:black (221, 39, 39);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image: url(lolgirl.jpg);
                background-size: cover;
            }
            .insight {
                color:black (221, 39, 39);
            }
            .hr1 {
                width: 130px;
                color:black (221, 39, 39);
            }
            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: left;
                position: relative;
                top: 20px;
                color:black (150, 39, 39);
            }
            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                top: 40px; 
                color:black (221, 39, 39); 
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:black (221, 39, 39);
                top: 90px;
                position: relative;
            }
            .pic {
                position: relative;
                top: 150px;
                left: 250px;
                width: 100px;
                height: 100px;
                background-size: cover;
                color:black (221, 39, 39);
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 200px;
                color:black (221, 39, 39);
            }
            .name {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color:black (221, 39, 39);
                top: 210px;
            }
            .pub {
                font-size: large;
                position: relative;
                top: 180px;
                left: 330px;
                color:black (221, 39, 39);
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1> Full Stack Foundations<br> </h1>

            </div>
            <div class="para">
                <p> A Complete Guide For
                    <br> Developers </p>
            </div>
            <div class="pic">
                <img src="rrrr.jpg" width="150" height="150" >
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>Ragavi Krishnan</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> Third Edition </b>
            </div>
        </div>
    </body>
</html>

```
## OUTPUT:
![Screenshot 2023-12-14 113736](https://github.com/Ragavikrishnan/cover/assets/144870428/c958c787-797f-4e41-8092-ad87f13b1e2a)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
