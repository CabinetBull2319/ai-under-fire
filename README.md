<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Player</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: Arial, sans-serif;
        }

        .container {
            text-align: center;
        }

        video {
            width: 800px;
            height: 600px;
            max-width: 90%;
            border: 2px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .ready-button {
            margin-top: 30px;
            padding: 15px 30px;
            font-size: 18px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .ready-button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/WewFzGNaqxI?si=uVRWcA2MK_f0E_Gl&amp;controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <br>
        <a href="AI Under Fire Version 0.32.html"><button class="ready-button">I am ready!</button></a>
    </div>
</body>
</html>
