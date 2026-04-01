- 👋 Hi, I’m @jilaliabdraoiuf
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
jilaliabdraoiuf/jilaliabdraoiuf is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سيارة تفاعلية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        h1 {
            margin-top: 20px;
            color: #333;
        }
        .car {
            position: relative;
            width: 300px;
            height: 150px;
            margin: 50px auto;
            background-color: #007BFF;
            border-radius: 20px;
        }
        .door {
            position: absolute;
            width: 50px;
            height: 100px;
            background-color: #333;
            transition: transform 0.5s;
            top: 25px;
        }
        .left-door {
            left: 0;
            transform-origin: left;
        }
        .right-door {
            right: 0;
            transform-origin: right;
        }
        .open {
            transform: rotateY(-90deg);
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>سيارة تفاعلية</h1>
    <div class="car">
        <div class="door left-door"></div>
        <div class="door right-door"></div>
    </div>
    <button onclick="openDoors()">فتح/إغلاق الأبواب</button>

    <script>
        function openDoors() {
            const doors = document.querySelectorAll('.door');
            doors.forEach(door => door.classList.toggle('open'));
        }
    </script>
</body>
</html>
