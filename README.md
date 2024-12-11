# PART-1

<html>
    <head>
        <title>MY WEB PAGE</title>
        <style>
            h1{
                font-size: 20px;
                color: pink;
            }
            .div{
                background-color: red;
            }
            #line{
                border: 2px solid blue;
            }
        </style>
    </head>
    <body>
        <h1>MY WEB PAGE</h1>
        <div class="div">
            <p id="line">This is my paragraph.</p>
        </div>
    </body>
</html>

# PART-2

<html>
    <head>
        <title>MY WEB PAGE</title>
        <style>
            
        h1 {
            color: blue; /* Changes the color of all <h1> elements to blue */
        }

        p {
            font-size: 18px; /* Sets the font size of all <p> elements */
            font-family: Arial, sans-serif; /* Sets the font style of all <p> elements */
        }

        .highlight {
            background-color: yellow; /* Adds a yellow background for elements with class 'highlight' */
        }
    </style>

    <!-- Link to External CSS -->
    <link rel="stylesheet" href="styles.css">
       
    </head>
    <body>
        <!-- Inline CSS to style one element -->
        <h1 style="color: red;">This is an Inline Styled Heading</h1>

        <!-- Elements styled using Internal CSS -->
        <p>This is a paragraph styled using internal CSS.</p>
        <p class="highlight">This paragraph has a yellow background using internal CSS class.</p>

        <!-- A link to demonstrate hover effect from external CSS -->
        <a href="#">This is a link styled using external CSS</a>
    </body>
</html>
#CSS FILE
/* External CSS file to style the entire webpage */

/* Change the background color of the webpage */
body {
    background-color: #f4f4f9; /* Light gray background */
}

/* Style for links with hover effects */
a {
    color: #333; /* Default link color */
    text-decoration: none; /* Remove underline from links */
}

a:hover {
    color: #ff5733; /* Change link color when hovered */
    text-decoration: underline; /* Add underline when hovered */
}

# PART-3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Card Component</title>

    <!-- Internal CSS -->
    <style>
        /* Global styles */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        /* Card container */
        .card {
            background-color: #ffffff; /* Light background color */
            border: 1px solid #ddd; /* Subtle border */
            border-radius: 8px; /* Rounded corners */
            width: 300px;
            margin: 20px; /* Margin around the card */
            padding: 20px; /* Padding inside the card */
            box-shadow: 0 4px 6px rgba(0,0,0,0.1); /* Light shadow */
            text-align: center; /* Center-align the content */
        }

        /* Card title */
        .card-title {
            font-size: 24px; /* Font size */
            font-weight: bold; /* Bold text */
            color: #333; /* Dark text color */
            margin-bottom: 10px; /* Spacing between title and paragraph */
        }

        /* Card description */
        .card-description {
            font-size: 16px; /* Font size */
            color: #666; /* Gray color for description */
            text-align: justify; /* Justify paragraph text */
            line-height: 1.6; /* Line height for better readability */
        }
    </style>
</head>
<body>

    <!-- Simple Card Component -->
    <div class="card">
        <h2 class="card-title">My Card</h2>
        <p class="card-description">
            This is a simple card component designed using HTML and CSS. 
            It features a heading, a description, padding for internal spacing, 
            and a clean border to distinguish it from the background.
        </p>
    </div>

</body>
</html>
