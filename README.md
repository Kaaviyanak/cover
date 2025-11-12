# Ex.06 Book Front Cover Page Design
## Date:12:11:25

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Future of Deep Learning</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #e6ebef;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: linear-gradient(
          rgba(0, 0, 0, 0.5),
          rgba(0, 0, 0, 0.7)
        ),
        url('https://images.unsplash.com/photo-1555949963-aa79dcee981c?auto=format&fit=crop&w=800&q=80');
      background-size: cover;
      background-position: center;
      border-radius: 10px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
      color: white;
      position: relative;
      overflow: hidden;
      padding: 30px;
      box-sizing: border-box;
    }

    .publisher {
      font-size: 14px;
      font-weight: bold;
      letter-spacing: 1px;
      color: #e0e0e0;
    }

    .title {
      font-size: 28px;
      font-weight: 700;
      text-transform: uppercase;
      margin-top: 40px;
      line-height: 1.2;
      color: #00ffcc;
    }

    .subtitle {
      margin-top: 10px;
      font-size: 15px;
      color: #ccf5ff;
      line-height: 1.4;
    }

    .edition {
      position: absolute;
      bottom: 80px;
      left: 30px;
      font-size: 16px;
      color: #ff6666;
      font-weight: bold;
    }

    .author-name {
      position: absolute;
      bottom: 60px;
      left: 30px;
      font-size: 16px;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .author-photo {
      position: absolute;
      bottom: 20px;
      right: 25px;
      width: 90px;
      height: 100px;
      border-radius: 6px;
      overflow: hidden;
      border: 2px solid #fff;
      box-shadow: 0 0 8px rgba(255, 255, 255, 0.5);
    }

    .author-photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .footer {
      position: absolute;
      bottom: 10px;
      left: 30px;
      font-size: 14px;
      color: #f0f0f0;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="publisher">VISIONARY PRESS</div>

    <div class="title">THE FUTURE OF<br>DEEP LEARNING</div>

    <div class="subtitle">
      Exploring the Depths of Neural Networks,<br>
      Algorithms, and Artificial Minds
    </div>

    <div class="edition">Limited Edition</div>

    <div class="author-name">KAAVIYAN K</div>

    <div class="author-photo">
      <img src="c:\Users\lenovo\Downloads\c004f1f6-069e-4616-b03b-d6b5c0b98fa9.jpg" alt="Author Photo">
    </div>

    <div class="footer">AI & ML</div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.


