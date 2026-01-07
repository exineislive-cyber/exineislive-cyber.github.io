<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>EXINE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">

    <img src="profile.png" class="profile-img">

    <div class="name">
        EXINE <span class="verify">✔</span>
    </div>

    <a href="games.html" class="btn">
        <img src="https://cdn-icons-png.flaticon.com/512/3612/3612569.png">
        <span>GAMES</span>
    </a>

</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Android Games</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">

    <img src="profile.png" class="profile-img">

    <div class="name">
        EXINE <span class="verify">✔</span>
    </div>

    <a href="minecraft.html" class="btn">
        <img src="https://cdn-icons-png.flaticon.com/512/226/226770.png">
        <span>ANDROID GAMES</span>
    </a>

</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Minecraft Android</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">

    <img src="profile.png" class="profile-img">

    <div class="name">
        EXINE <span class="verify">✔</span>
    </div>

    <a href="https://t.me/+bSVwtW0UpK45MjU1" target="_blank" class="btn">
        <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/6/6b/Grass_Block.png">
        <span>MINECRAFT (ANDROID)</span>
    </a>

</div>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: black;
    font-family: Arial, sans-serif;
    height: 100vh;
}

.container {
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 80px;
}

.profile-img {
    width: 90px;
    height: 90px;
    border-radius: 12px;
    object-fit: cover;
    margin-bottom: 20px;
}

.name {
    font-size: 36px;
    font-weight: bold;
    color: #c7ff00;
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 30px;
}

.verify {
    color: #00aaff;
    font-size: 18px;
}

.btn {
    width: 80%;
    max-width: 500px;
    background: #1a1a1a;
    padding: 16px;
    border-radius: 12px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 14px;
    text-decoration: none;
    color: white;
    font-size: 16px;
    font-weight: bold;
}

.btn img {
    width: 28px;
    height: 28px;
}
