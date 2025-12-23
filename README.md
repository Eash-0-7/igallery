# Ex.08 Design of Interactive Image Gallery
## Date:

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
html code
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Interactive Image Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h2>PORSCHE</h2>
    <div class="gallery">
        <img src="p1.avif" alt="Image 1">
        <img src="p2.avif" alt="Image 2">
        <img src="p3.avif" alt="Image 3">
        <img src="p4.avif" alt="Image 4">
        <img src="p5.avif" alt="Image 5">
        <img src="p6.avif" alt="Image 6">
        <img src="p7.avif" alt="Image 7">
        <img src="p8.avif" alt="Image 8">

    </div>

</body>

</html> 

css code 

/* style.css */
body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #f8f9fa;
    margin: 0;
    padding: 20px;
}

h2 {
    text-align: center;
    color: #333;
    margin-bottom: 30px;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    max-width: 800px;
    margin: auto;
}

.gallery img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    cursor: pointer;
}

.gallery img:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}


## OUTPUT:
<img width="1208" height="1468" alt="Igallery" src="https://github.com/user-attachments/assets/790e7f5e-3ea2-4e92-9983-3e899dbbd2e8" />

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
