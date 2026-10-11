
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>আমার ওয়েবসাইট</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }
        .container {
            background: rgba(255, 255, 255, 0.1);
            padding: 40px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        p {
            font-size: 1.1rem;
            margin-bottom: 25px;
            color: #e0e0e0;
        }
        .btn {
            display: inline-block;
            text-decoration: none;
            background: #ff758c;
            color: white;
            padding: 12px 30px;
            border-radius: 25px;
            font-weight: bold;
            transition: 0.3s ease;
        }
        .btn:hover {
            background: #ff7eb3;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>স্বাগতম আমার ওয়েবসাইটে!</h1>
        <p>এটি গিটহাবে হোস্ট করা আমার প্রথম লাইভ ওয়েবসাইট।</p>
        <a href="https://github.com" target="_blank" class="btn">গিটহাব ভিজিট করুন</a>
    </div>

</body>
</html>
