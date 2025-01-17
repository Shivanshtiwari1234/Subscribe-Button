Subscribe Button

A simple, styled "Subscribe" button created using HTML and CSS.

Features:
- Red button with white text.
- Hover and active states with smooth opacity transitions.
- Responsive design for different screen sizes.

Installation:
1. Clone the repository:
   
   git clone https://github.com/yourusername/Subscribe-Button.git

2. Open the subscribe.html file in any browser to see the button.

Usage:
To use the subscribe button in your project, you can copy the HTML and CSS code from subscribe.html into your project files.

<!DOCTYPE html>
<html>
<head>
    <title>Subscribe</title>
    <style>
        body {
            font-family: Arial;
            text-align: center;
            margin-top: 20%;
        }
        .subscribe-button {
            background-color: rgb(204, 0, 0);
            color: white;
            border: none;
            border-radius: 5px;
            margin: 10px;
            padding: 10px;
            transition: opacity 0.15s;
            display: inline-block;
        }
        .subscribe-button:hover {
            opacity: 0.7;
        }
        .subscribe-button:active {
            opacity: 0.4;
            transition: none;
        }
    </style>
</head>
<body>
    <button class="subscribe-button">SUBSCRIBE</button>
</body>
</html>

License:
This project is licensed under the MIT License - see the LICENSE file for details.
