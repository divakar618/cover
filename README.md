# Ex.06 Book Front Cover Page Design
## Date: 25/10/23

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

        .bookpage{
            width: 400px;
            height: 600px;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(photo3.jpg);
            background-size: cover;
        }
            

        .insight{
            color: red;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 20px;
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
            color: red;
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
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>POWER OF MONEY</h1></div>
            <div class="subtitle">
                MONEY HAS MORE POWER TO CHANGE THE WORLD
            </div>
            <div class="mypic">
                <img src="photo4.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: red;">
            </div>
            <div class="author">
               <p><b>BY Divakar</b></p>
            </div>
            <div class="pub">
                OPEN >>>
            </div>
            <div class="ed">
                <b>Special Update</b>
            </div>
        </div>
    </bodY>
</html>
```


## OUTPUT:
![Screenshot 2023-11-14 144518](https://github.com/divakar618/cover/assets/121932143/fd07469d-c74c-42eb-b8b5-28644029b38a)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
