# Ex.06 Book Front Cover Page Design
## Date:3.12.2024

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
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 450px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url("book.jpg");
            background-size: cover;
            text-align: center;
        }
            
        
        .insight{
            color:rgb(234, 240, 240);
            font-family: Trebuchet MS;
            bottom:450px;
            top:350px;
            border:none;
        }
        .hrstyle{
            width:100px;
        } 
                 
    
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:300px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: 'Times New Roman', Times, serif;
            font-size: large;
            text-align: center;
            position: relative;
            top: 6px;

        
        }
        .id {
            width:400px;
            position:relative;
            top:300px;
            left:23px;
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(132, 241, 209);
            font-size: large;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position:relative;
            bottom:156px;
            
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
            text-align: center;
        }
        .sub{
            color:azure;
            font-family:Arial, Helvetica, sans-serif;
            font-size: large;
            position:relative;
            bottom:200px;
            top:450px;
        }
        .mypic{
            position: relative;
            top: 260px;
            left: 270px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        .lpic{
            position: relative;
            bottom: 100px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            
            <div class="hrstyle">
                <hr style="color:rgb(245, 14, 14)">
            </div>
            <div class="booktitle">
                <h1 style="font-family: 'Times New Roman', Times, serif;">IoT Enabling Technology</h1></div>

            <div class="sub">
                Making Everyday Life Smarter With IoT Technology
           </div>

            <div class="mypic">
                <img src="keerthana.jpg" width="120" height="120" >
            </div>
            <div class="id">
                <hr style="color:rgba(96, 6, 117, 0.163)">
            </div>
            <div class="author">
               <p><b>KEERTHANA D</b></p>
            </div>
            <div class="ed">
                <b>Connecting You to a Connected World</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:

![alt text](<Screenshot (60).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
