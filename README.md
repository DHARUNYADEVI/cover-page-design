# cover-page-design
## AIM:
To design a book front cover page using HTML and CSS.

## Design Steps:

### Step 1:
Create a Django admin project.
### Step 2:
Create an app in the django interface.
### Step 3:
Create a folder named 'static' in the app folder.
### Step 4:
Create a new HTML file in the static folder.
### Step 5:
write the HTML code with relevant CSS properties.
### Step 6:
Choose the appropriate style and color scheme.
### Step 7:
Insert the images in their appropriate places.
### Step 8:
Publish the website in the localhost.

## Program:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:navy;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bg.png);
            background-size: cover;
        }
            

        .insight{
            color: black;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: black;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
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
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: blue;
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
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rebeccapurple;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="image.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:rebeccapurple;">
            </div>
            <div class="author">
               <p><b>DHARUNYADEVI S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```
## Output:
![Screenshot from 2023-12-12 04-07-11](https://github.com/DHARUNYADEVI/cover-page-design/assets/147473847/e8843589-ab1e-408d-ae8f-9277c4456c99)
## Result:
The program for designing a book front cover page using HTML and CSS is completed successfully.
