# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

Step 1:
Create a Django Admin project.

Step 2:
Create an app in the Django interface.

Step 3:
Create a folder named 'static' in the app folder.

Step 4:
Create a new HTML file in the static folder.

Step 5:
Write the HTML code with relevant CSS properties.

Step 6:
Choose the appropriate style and color scheme.

Step 7:
Insert the images in their appropriate places.

Step 8:
Publish the website in the LocalHost.


## Code:
```
<!DOCTYPE html>
<html>

<head>
    <title>CSE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(back.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: Roquen;
            font-size: larger;
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
            color:azure;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:azure;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
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
            <div class="insight">
                MUSIC
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>INTRODUCTION TO COMPUTER SCIENCE</h1></div>
            <div class="subtitle">
                 books for beginners
            </div>
            <div class="subtitle">
                 Top seller of 2023
            </div>

            <div class="mypic">
                <img src="img.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>ROHITH V</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>

## Output:
![Screenshot 2023-12-29 132356](https://github.com/23004742/cover-page-design/assets/150319318/d66dfd84-9ae7-4e34-9539-b124954d84d2)


## Result:
The program for designing book front cover page using HTML and CSS is completed successfully.

