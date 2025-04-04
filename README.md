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
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>CSS Styling Example</title>
  <!-- Link to the external CSS file -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header section with an ID and class for styling -->
  <header>
    <h1 id="main-title" class="title">Welcome to My Website</h1>
  </header>

  <!-- Main content section -->
  <section>
    <p class="description">
      This is a sample webpage styled using an external CSS file. It demonstrates the use of different selectors, typography, and spacing.
    </p>
    <!-- Styled external image -->
    <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" 
         alt="Beautiful Landscape" class="responsive-image">
  </section>

  <!-- Footer section -->
  <footer>
    <p class="footer-text">© 2025 My Website</p>
  </footer>
</body>
</html>


/* Apply styles to the body element */
body {
  font-family: 'Georgia', serif;  /* Using a different font for readability */
  background-color: #f4f4f4;
  margin: 0;
  padding: 0;
}

/* ID selector for the main title */
#main-title {
  color: #333;
  text-align: center;
  margin-top: 20px;
}

/* Class selector for the description paragraph */
.description {
  font-size: 18px;
  color: #555;
  padding: 15px;
  margin: 20px auto;
  width: 80%;
  border: 2px solid #ccc;  /* Border to highlight the paragraph */
}

/* Class selector for styling the image */
.responsive-image {
  display: block;
  margin: 20px auto;
  max-width: 90%;
  height: auto;
  border: 5px solid #fff;  /* White border around the image */
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);  /* Subtle shadow effect */
}

/* Class selector for the footer text */
.footer-text {
  text-align: center;
  padding: 20px;
  background-color: #333;
  color: #fff;
  margin: 0;
}

