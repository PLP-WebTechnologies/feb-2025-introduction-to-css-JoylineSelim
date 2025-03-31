# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Styled Page</h1>
    </header>

    <!-- Image Section -->
    <section>
        <img src="https://images.pexels.com/photos/34950/pexels-photo-34950.jpeg" alt="A beautiful landscape" class="styled-image">
    </section>

    <!-- Main Content Section -->
    <section class="content">
        <h2>About This Page</h2>
        <p>This page is styled with external CSS to improve readability and aesthetics. It demonstrates the use of different selectors, fonts, colors, and spacing.</p>
    </section>

    <!-- Button Section -->
    <section>
        <button id="cta-button">Click Me</button>
    </section>

</body>
</html>

CSS
/* Apply a background color and font to the entire page */
body {
    background-color: #f4f4f9;
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

/* Header styling */
header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    margin-bottom: 20px;
}

/* Style the image with margin and border */
.styled-image {
    width: 100%;
    height: auto;
    border: 5px solid #ddd;
    margin: 20px 0;
}

/* Main content styling */
.content {
    padding: 20px;
    margin: 0 15%;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Button styling using ID selector */
#cta-button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

#cta-button:hover {
    background-color: #45a049;
}

/* Styling paragraph text with a class selector */
.content p {
    line-height: 1.6;
    font-size: 18px;
    color: #333;
}


