# wallpaper
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>White Red Lines</title>

<style>
html, body{
    margin:0;
    width:100%;
    height:100%;
    overflow:hidden;
    background:white;
}

body{
    position:relative;
}

/* 빨간 선 */
.line{
    position:absolute;
    width:2600px;
    height:18px;
    background:#ff0000;
    transform-origin:left center;
    transform:rotate(135deg);
}

/* 선 위치 */
.line1{
    left:950px;
    top:180px;
}

.line2{
    left:1250px;
    top:480px;
}

.line3{
    left:1550px;
    top:780px;
}
</style>

</head>
<body>

<div class="line line1"></div>
<div class="line line2"></div>
<div class="line line3"></div>

</body>
</html>
