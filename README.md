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
Developed by: LAVANYA M
Register number: 212222110021
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #0b0b0bfb;
            color:rgb(231, 230, 230);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        
            background-image:url("img.jpg"),url("img2.png");
            background-size :80% 70% 50% 30%; 
            background-repeat: no-repeat;     
         }
            

        .toptext{
            color:thistle;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            text-align: left;
            color:yellow;
            top:130px;
            
            font-family:'ink free';
            font-size: large;
        }
        .booktitle{
            font-family: 'gabriola', monospace;
            font-size: large  ;
            text-align: center;
            position: relative;
            top: 180px;
            color:rgb(229, 108, 28);
        
        }
        
    
        .edition{
            color:yellow;
            font-size: large;
            font-family: 'ink free';
            text-align: right;
            position:relative;
            top: 200px;

        }
        .sub{
            font-family:'Segoe script';
            font-size: medium;
            text-align: center;
            position: relative;
           
            color: rgb(92, 230, 212);

        }
        .subtitle{
            font-family:'Segoe script';
            font-size: large;
            text-align: center;
            position: relative;
            top:220px;
            color: rgb(236, 244, 243);
        }
        .photo{
            position: relative;
            top: 189px;
            left: 300px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        .text-container {
            position: absolute;
            top: 500px;
            left: 558px; 
            color:rgb(217, 207, 207);
            font-size: x-large;
            font-family: 'cambria math',sans-serif ;
        }

         .text-containers {
            position: absolute;
            top: 540px;
            left: 580px; 
            color:rgb(218, 200, 200);
            font-size: x-large;
            font-family: 'cambria math',sans-serif;
        }

        .text-containerss {
            position: absolute;
            top: 580px;
            left: 630px; 
            color:rgb(220, 62, 62);
            font-size: x-large;
            font-family:  'cambria math',sans-serif;
        }
 

         
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>

        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>

            <div class="tophr">
                <hr style="color: red;">
            </div>

            <div class="subtitle">
            </div>

            <div class="subtitle">
            </div>    

            <div class="booktitle">
                <h1>AND THEN THERE WERE NONE </h1>
            </div>
            <div class="sub">
                Enter into the world of suspense and thriller
            </div>

            <div class="subtitle">
               Find Out The MYSTERY That happens to 10 strangers who visit an island that leads to a murder. Who would be the murderer?
            </div>
            

            <div class="photo">
                <img src="img3.jpg" width="100" height=100" >
            </div>
               
            <div class="text-container">
               <p> FIND </p> 
            </div>

            <div class="text-containers">
               <p>WHO IS THE  </p> 
            </div>

            <div class="text-containerss">
               <p> CULPRIT ??</p> 
            </div>

            <div class="edition">
                <b> AGATHA CRISTIE</b>
            </div>
          
            
        </div>
    </body>
</html>

```

## OUTPUT:
![output](<Screenshot 2023-11-13 114751.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
