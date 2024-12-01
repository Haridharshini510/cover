# Ex.06 Book Front Cover Page Design
## Date:1/12/24

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
bookcover.html

<!DOCTYPE html>
<html>
    <head>
      <link rel="stylesheet" href="style.css">
    </head>
    <body>
           <div class="container">
            <div class="item6">
                <h3>BEST SELLER!</h3>
            </div>
               <div class="item1">
                   <h1>TECHSPRINT TOWARDS<br> MERN STACK.</h1>
               </div>
               <div class="item2">
                   <h3>Embark on the journey to master Mern stack.</h3>
               </div>
               <div class="item3">
                   <h3>SECOND EDITION</h3>
               </div>
               <img src="pic.jpg" alt="image">
               <div class="item4">
                   <h3>HARIDHARSHINI J</h3>
               </div>
               <div class="item5">
                   <h3>SEC</h3>
           </div>
       </div>
    </body>
</html>

style.css

body{
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(26, 72, 118);
}
.container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items:start;
    height: 100vh;
    width: 50%;
    background-image: url('web2.jpg'); 
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
}
.item1{
    position: absolute;
    top:70px;
    left:480px;
    font-size: 14px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight:bolder;
}
.item2{
    position: absolute;
    top:140px;
    left:480px;
    font-size: 14px;
}
.item3{
    position: absolute;
    left:470px;
    bottom: 85px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
font-family: monospace;
}
.item4{
    position: absolute;
    left:470px;
    bottom: 55px;
    font-family: fantasy;
    font-weight: 100;
}
    .item5{
    position: absolute;
    right: 440px;
    bottom: 50px;
    font-size: 20px;
    font-family:monospace;
}
.item6{
    position: absolute;
    top:26px;
    left: 440px;
    font-size: 12px;
    font-family: cursive;

}
img{
    height: 100px;
    position: absolute;
    right: 440px;
    bottom: 100px;
}
```

## OUTPUT:
![alt text](<Screenshot (38).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
