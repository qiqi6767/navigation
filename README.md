<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>网址导航</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }

        h1 {
            font-size: 2rem;
            margin: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
            background-color: #fff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .link-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .link-list li {
            margin: 1rem 0;
            display: flex;
            align-items: center;
        }

        .link-list a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        .link-list img {
            width: 24px;
            height: 24px;
            margin-right: 0.5rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>网址导航</h1>
    </header>
    <div class="container">
        <ul class="link-list">
            <li>
                <img src="link-icon.png" alt="Link Icon">
                <a href="https://www.google.com">Google</a>
            </li>
            <li>
                <img src="link-icon.png" alt="Link Icon">
                <a href="https://www.facebook.com">Facebook</a>
            </li>
            <li>
                <img src="link-icon.png" alt="Link Icon">
                <a href="https://www.twitter.com">Twitter</a>
            </li>
            <!-- 添加更多链接 -->
        </ul>
    </div>
</body>
</html>
