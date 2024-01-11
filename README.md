<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        h1 {
            margin: 20px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .box {
            float: left;
            width: 30%;
            padding: 20px;
            background: #fff;
            margin: 2%;
            box-sizing: border-box;
            text-align: center;
        }
        button {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Simple Website</h1>
    </header>
    <div class="container">
        <div class="box">
            <h2>Feature 1</h2>
            <p>This is the content for Feature 1.</p>
            <button onclick="alert('You clicked Feature 1')">Click me</button>
        </div>
        <div class="box">
            <h2>Feature 2</h2>
            <p>This is the content for Feature 2.</p>
            <button onclick="alert('You clicked Feature 2')">Click me</button>
        </div>
        <div class="box">
            <h2>Feature 3</h2>
            <p>This is the content for Feature 3.</p>
            <button onclick="alert('You clicked Feature 3')">Click me</button>
        </div>
    </div>
</body>
</html>
