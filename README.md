# Ex.06 Book Front Cover Page Design
## Date:

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
```<html>
<head>
<meta name="covermap"
content="width=device-width,initial-sacale=1.0">
<style>
.bookpage{
width:400px;
height:600px;
color: rgb(144, 276, 134);
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: 'Franklin Gothic Medium','Franklin Gothic Medium','Cooper Black','sans-serief';
background-image: url(back.png.png);
background-size: cover;
}

.insight{
color:cyan;
}

.hrstyle{
width: 100px;
}

.author{
display: inline;
position: relative;
color:gold;
top: 190px;
font-family: Georgia;
font-size: medium;
}


.booktitle{
font-family:'Cooper Black';
color:purple;
font-size: Medium;
text-align: center;
position: relative;
top: 30px;
}

.id{
width:400px;
position: relative;
top:180px;
}

.pub{
font-size:medium;
position: relative;
color:pink;
top:155px;
left:330px;
}

.ed{
color:green;
font-size: medium;
font-family: 'Cooper Black';
position:relative;
top:85px;
}

.subtitle{
font-family:'Lemon Bold';
font-size:large;
position: relative;
top: 25px;
}


.mypic{
position:relative;
top:140px;
left:260px;
width:100px;
height:100px;
background-size:cover;
}

</style>
<title>Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="insight">
  SEC INSIGHT
</div>
<div class="booktitle">
<h1>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</h1></div>
<div class="subtitle">
FROM HTML AND CSS
</div>
<div class="mypic.png">
<img src="mypic" width="130" height="145" alt="">
</div>
<div class="id">
<hr style="color:rgb(255, 255, 255);">
</div>
<div class="author">
<p><b>SRISHA.M</b></p>
</div>
<div class="pub">
    SEC
</div>
<div class="ed">
<b>NINTH Edition</b>
</div>
</div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-11 113438.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
