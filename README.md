<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classroom Activity</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4);
            color: #333;
            text-align: center;
        }
        header {
            background: #222;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
            border-radius: 10px;
        }
        h1 {
            color: #ff6f61;
        }
        p {
            line-height: 1.6;
        }
        button {
            padding: 10px 20px;
            border: none;
            background: #ff6f61;
            color: white;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
            transition: 0.3s;
        }
        button:hover {
            background: #e05549;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 10px;
            margin-top: 20px;
        }
        .box {
            background: #ffb6b9;
            padding: 20px;
            border-radius: 5px;
            font-weight: bold;
        }
        footer {
            background: #222;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>Welcome to My Classroom Activity</header>
    <div class="container">
        <h1>Explore Styling & Formatting</h1>
        <button onclick="alert('You clicked me!')">Click Me</button>
        <div class="grid">
            <div class="box">Box 1</div>
            <div class="box">Box 2</div>
            <div class="box">Box 3</div>
            <div class="box">Box 4</div>
        </div>
    </div>
    <footer>© 2025 Classroom Activity. All rights reserved.</footer>
</body>
</html>
