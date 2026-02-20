# Ex.05 Book Front Cover Page Design
## Date:20/02/2026

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
book.html
```
!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>3D Book Cover</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <div class="book-container">

    <div class="publisher">DISNEY BOOKS</div>

    <div class="branding">DISNEY</div>

    <div class="title">THE SLEEPING BEAUTY</div>

    <!-- ✅ Center Paragraph -->
    <div class="description">
      This book explores the magical journey of Sleeping Beauty,
      her enchanted castle, and the timeless power of true love.
      A beautiful fairy tale filled with adventure and wonder.
    </div>

    <div class="edition">FOURTH EDITION</div>

    <div class="author"><b>SRISHA</b></div>

    <div class="image-frame">
      <img src="img1.jpg" alt="Author">
    </div>

  </div>
</body>
</html>
```
style.css
```
body {
  margin: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: radial-gradient(circle at center, #1e1f26, #121217);
  font-family: Arial, sans-serif;
}

.book-container {
  width: 420px;
  height: 600px;
  border-radius: 20px;
  padding: 30px;
  color: white;
  position: relative;
  overflow: hidden;

  /* Background Image */
  background-image: url("coverbg.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

  box-shadow: 15px 15px 30px #0d0e12,
              -15px -15px 30px #2c2f36;
}

.publisher {
  position: absolute;
  top: 30px;
  right: 30px;
  font-size: 14px;
  color: black;
}

.branding {
  text-align: center;
  font-size: 20px;
  color: #ffcc00;
  margin-top: 40px;
}

.title {
  font-size: 26px;
  font-weight: bold;
  text-align: center;
  margin-top: 30px;
  letter-spacing: 1px;
  color:goldenrod;
}

.subtitle {
  font-size: 18px;
  text-align: center;
  margin-top: 10px;
  color:darkorange
}


.highlight-line {
  height: 3px;
  width: 60%;
  background: #ff9800;
  margin: 30px auto;
  border-radius: 50px;
}
.description {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

  width: 80%;
  text-align: center;
  font-size: 15px;
  line-height: 1.6;
  color:black;
}

.edition {
  position: absolute;
  bottom: 80px;
  left: 30px;
  font-size: 14px;
  color:goldenrod;
}

.author {
  position: absolute;
  bottom: 30px;
  left: 30px;
  font-size: 16px;
  color: purple;
}

.image-frame {
  position: absolute;
  bottom: 30px;
  right: 30px;
  width: 110px;
  height: 140px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
}

.image-frame img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```


## OUTPUT:
<img width="1911" height="1086" alt="Screenshot 2026-02-20 112204" src="https://github.com/user-attachments/assets/91b8a629-ee61-4a4d-8c1b-d0589136b07c" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
