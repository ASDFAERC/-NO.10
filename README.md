<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>搞笑页面</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: lightblue;
            font-family: Arial, sans-serif;
        }
    </style>
    <script>
        function showMessage() {
            alert("哈哈！你上当了！");
        }
    </script>
</head>
<body>
    <button onclick="showMessage()">点击我</button>
</body>
</html>
