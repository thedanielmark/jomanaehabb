<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        #nyanCat {
            width: 100px; /* Set the initial width */
            transition: width 0.5s ease; /* Add a transition for a smooth effect */
        }

        #nyanCat:hover {
            width: 200px; /* Set the zoomed width on hover */
        }
    </style>
</head>
<body>
    <img id="nyanCat" src="nyan-cat.gif" alt="Nyan Cat">
</body>
</html>
