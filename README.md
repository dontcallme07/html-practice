<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>I'm Sorry</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            font-family: Arial, Helvetica, sans-serif;
            color: #333;
        }

        .box {
            background: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            max-width: 400px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        h1 {
            color: #e91e63;
        }

        button {
            padding: 10px 25px;
            margin: 10px;
            border: none;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
        }

        .yes {
            background: #4caf50;
            color: white;
        }

        .no {
            background: #f44336;
            color: white;
        }
    </style>
</head>

<body>

<div class="box" id="mainBox">
    <h1>I'm really sorry 😞🙏</h1>

    <p>
        Please mujhe maaf kar do 💗<br>
        Aakhri chance de do 🤞<br>
        Tum meri zindagi ho ❤️
    </p>

    <h3>Kya tumne mujhe maaf kiya?</h3>

    <button class="yes" onclick="forgiveYes()">✔️ Haan</button>
    <button class="no" onclick="forgiveNo()">❌ Nahi</button>
</div>

<script>
    function forgiveYes() {
        document.getElementById("mainBox").innerHTML = `
            <h1>Thank You 😭❤️</h1>
            <p>
                Tum sabse best ho 💗<br>
                I promise kabhi disappoint nahi karunga 🤞
            </p>
        `;
    }

    function forgiveNo() {
        document.getElementById("mainBox").innerHTML = `
            <h1>🎉 CONGRATULATIONS 🎉</h1>
            <p style="font-size:18px;">
                You love <b>Faraz</b> 😌❤️<br><br>
                Sach sach batao 😏
            </p>
        `;
    }
</script>

</body>
</html>

