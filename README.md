# Ex.06 Book Front Cover Page Design
## Date:20.05.2025

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
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Book Cover - The secret to becoming an alpha</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display&family=Montserrat:wght@500&display=swap');

  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    font-family: 'Montserrat', sans-serif;
    background: #111218;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .book-cover {
    width: 360px;
    height: 560px;
    border-radius: 20px;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 40px 30px;
    background: linear-gradient(145deg, #a68513, #f9d976, #a68513);
    background-size: 400% 400%;
    animation: shimmer 8s ease infinite;

    /* Chrome metallic effect */
    box-shadow:
      inset 0 0 25px 8px rgba(255, 255, 255, 0.4),
      0 10px 25px rgba(166, 134, 19, 0.65),
      0 0 25px 6px rgba(255, 247, 178, 0.45);
  }

  @keyframes shimmer {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

  .title {
    font-family: 'Playfair Display', serif;
    font-size: 2.8rem;
    font-weight: 900;
    line-height: 1.15;
    color: #3b2e0c; /* Darker brown */
    text-shadow:
      0 0 6px rgba(0,0,0,0.65),
      0 0 10px rgba(0,0,0,0.55);
  }

  .bottom-left-container {
    position: absolute;
    bottom: 25px;
    left: 30px;
    color: #3b2e0c; /* Darker brown */
    font-family: 'Montserrat', sans-serif;
    text-transform: uppercase;
    letter-spacing: 2.5px;
    text-shadow:
      0 0 8px rgba(0,0,0,0.7);
  }

  .bottom-left-text {
    font-weight: 700;
    font-size: 1.1rem;
    margin-bottom: 8px;
  }

  .author {
    font-weight: 600;
    font-size: 1.2rem;
    text-transform: none;
    letter-spacing: 0.5px;
    text-shadow:
      0 0 7px rgba(0,0,0,0.65);
  }

  /* Decorative polished metal sheen shapes along edges */
  .sheen-top-left,
  .sheen-bottom-right {
    position: absolute;
    border-radius: 20px;
    pointer-events: none;
    mix-blend-mode: screen;
    filter: blur(8px);
  }

  .sheen-top-left {
    top: 15px;
    left: 15px;
    width: 110px;
    height: 200px;
    background: linear-gradient(45deg, rgba(255,255,255,0.85), rgba(255,255,255,0) 80%);
  }

  .sheen-bottom-right {
    bottom: 40px;
    right: 35px;
    width: 150px;
    height: 250px;
    background: linear-gradient(225deg, rgba(255,255,255,0.75), rgba(255,255,255,0) 75%);
  }

  /* Gold diagonal lines for metallic texture */
  .decorative-lines {
    pointer-events: none;
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    border-radius: 20px;
    background-image: repeating-linear-gradient(
      45deg,
      rgba(255, 215, 0, 0.15),
      rgba(255, 215, 0, 0.15) 2px,
      transparent 3px,
      transparent 9px
    );
    z-index: 1;
  }
</style>
</head>
<body>
  <div class="book-cover" role="img" aria-label="Book cover for The secret to becoming an alpha by Keerthan D premium edition">
    <div class="title">The secret<br />to becoming<br />an alpha</div>

    <div class="bottom-left-container">
      <div class="bottom-left-text">premium edition</div>
      <div class="author">SHAGILAN </div>
    </div>

    <div class="decorative-lines"></div>
    <div class="sheen-top-left"></div>
    <div class="sheen-bottom-right"></div>
  </div>
</body>
</html>
```

## OUTPUT:
![WhatsApp Image 2025-05-23 at 21 05 39_eaecc2fd](https://github.com/user-attachments/assets/091098be-6dbe-4b93-a5b0-d21d2b249c4f)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
