# 1111
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>bujue的网站</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to My Website 欢迎来到我的网站</h1>
    <h2>南华大学</h2>
    <p>简称南华 University of South China</p>
    <p>南华大学是湖南省国内一流大学建设高校综合性大学</p>
    <p>是国家中西部高校基础能力建设工程支持建设高校。</p>
    <p>校园面貌</p>
    <img src="F:\vscode--code\Example Image\OIP-C.jfif" alt="Example Image">
    <button onclick="changeImage()">更换图片</button>
    <script src="script.js"></script>
</body>
</html>
function changeImage() {
    var img = document.querySelector('img');
    img.src = "F:/vscode--code/Example Image/OIP-C1.jfif";
}
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

img {
    max-width: 100%;
    height: auto;
}


