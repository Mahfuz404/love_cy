
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Calculator</title>
    <style>
        body {
            background-image: url('https://i.ibb.co.com/Z6gbQwn/images-18.jpg');
            background-size: cover;
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        .container {
            max-width: 500px;
            margin: auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
        }
        input {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }
        button {
            background: linear-gradient(45deg, #ff0066, #ffcc00);
            color: #fff;
            border: none;
            padding: 15px 20px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            animation: bounce 1.5s infinite;
        }
        button:hover {
            background: linear-gradient(45deg, #ffcc00, #ff0066);
        }
        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        h1 {
            font-family: 'Brush Script MT', cursive;
            font-size: 50px;
        }
        p.result {
            font-size: 24px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Love Calculator</h1>
        <form method="post">
            <input type="text" name="name1" placeholder="Your Name" required>
            <input type="text" name="name2" placeholder="Partner's Name" required>
            <button type="submit">Calculate</button>
        </form>

        
        <p style="margin-top: 20px; font-family: 'Courier New', Courier, monospace;">Powered By @Mahfuz420</p>
    </div>
</body>
</html>
