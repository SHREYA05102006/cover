# Ex.06 Book Front Cover Page Design
## Date:7.12.24

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
background-image: url(cover.jpeg);
background-size: cover;
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
.ed{
color:azure;
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
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
<div class="booktitle">
<h1> <FONT color="black">Beyond the Stars: A Love Unknown</h1></div></FONT>
<br>
<div class="subtitle">
<center><font color="white">A Journey Across Worlds, A Love That Defies Time </center></font>
</div>
<br>
<br>
<br>
<br>

<div class="mypic">
<img src="photo.jpeg" width="90" height="90" >
</div>
<div class="id">
<hr style="color:blanchedalmond">
</div>
<div class="author">
<p><b>shreya</b></p>
</div>
<div class="ed">
<b>Bound by Stars</b>
</div>
</div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (162).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
