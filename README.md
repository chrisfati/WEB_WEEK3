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
            color: blue;
        }

        p {
            font-size: 18px;
            font-family: Arial, sans-serif;
        }

        .highlight {
            background-color: yellow;
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

# CSS FILE

/* External CSS file to style the entire webpage */

body {
    background-color: #f4f4f9;

a {
    color: #333;
    text-decoration: none;
}

a:hover {
    color: #ff5733;
    text-decoration: underline;
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
        .card {
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 300px;
            margin: 20px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
        }
        .card-title {
            font-size: 24px;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
        }
        .card-description {
            font-size: 16px;
            color: #666;
            text-align: justify;
            line-height: 1.6;
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
