- 👋 Hi, I’m @shiva930
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
shiva930/shiva930 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
<head>
    <title>Smiley Face</title>
    <style>
        .smiley {
            width: 100px;
            height: 100px;
            background: yellow;
            border-radius: 50%;
            position: relative;
        }

        .eyes {
            width: 20px;
            height: 20px;
            background: black;
            border-radius: 50%;
            position: absolute;
            top: 30px;
        }

        .eye-left {
            left: 30px;
        }

        .eye-right {
            right: 30px;
        }

        .mouth {
            width: 40px;
            height: 20px;
            border: 2px solid black;
            border-top-left-radius: 100px;
            border-top-right-radius: 100px;
            position: absolute;
            top: 50px;
            left: 30px;
        }
    </style>
</head>
<body>
    <div class="smiley">
        <div class="eyes eye-left"></div>
        <div class="eyes eye-right"></div>
        <div class="mouth"></div>
    </div>
</body>
</html>
