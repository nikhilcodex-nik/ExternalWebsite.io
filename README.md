<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Google</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #ffffff;
        }

        .logo {
            font-size: 90px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .logo span:nth-child(1) { color: #4285F4; }
        .logo span:nth-child(2) { color: #DB4437; }
        .logo span:nth-child(3) { color: #F4B400; }
        .logo span:nth-child(4) { color: #4285F4; }
        .logo span:nth-child(5) { color: #0F9D58; }
        .logo span:nth-child(6) { color: #DB4437; }

        .search-box {
            width: 550px;
            height: 45px;
            border-radius: 25px;
            border: 1px solid #dcdcdc;
            padding: 0 20px;
            font-size: 16px;
            outline: none;
        }

        .buttons {
            margin-top: 25px;
        }

        .buttons button {
            background-color: #f8f9fa;
            border: 1px solid #f8f9fa;
            padding: 10px 18px;
            margin: 5px;
            font-size: 14px;
            cursor: pointer;
            border-radius: 4px;
        }

        .buttons button:hover {
            border: 1px solid #c6c6c6;
        }
    </style>
</head>
<body>

    <div class="logo">
        <span>G</span><span>o</span><span>o</span><span>g</span><span>l</span><span>e</span>
    </div>

    <input type="text" class="search-box" placeholder="Search Google or type a URL">

    <div class="buttons">
        <button>Google Search</button>
        <button>I’m Feeling Lucky</button>
    </div>

</body>
</html>
