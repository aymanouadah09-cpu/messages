
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>رسالة خاصة ❤️</title>

    <style>
        body {
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
        }

        .card {
            width: 85%;
            max-width: 500px;
            background: white;
            padding: 35px;
            border-radius: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        h1 {
            color: #ff4f81;
        }

        input {
            width: 80%;
            padding: 15px;
            border: 2px solid #ff9a9e;
            border-radius: 25px;
            font-size: 18px;
            text-align: center;
        }

        button {
            margin-top: 20px;
            padding: 15px 30px;
            border: none;
            border-radius: 25px;
            background: #ff4f81;
            color: white;
            font-size: 18px;
        }

        #message {
            margin-top: 25px;
            font-size: 20px;
            color: #ff4f81;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <div class="card">

        <h1>رسالة خاصة ❤️</h1>

        <p>اكتبي اسمك 👇</p>

        <input type="text" id="name" placeholder="اكتبي اسمك هنا">

        <br>

        <button onclick="checkName()">
            اضغطي هنا ❤️
        </button>

        <div id="message"></div>

    </div>


    <script>

        function checkName() {

            let name = document.getElementById("name").value;

            if (name === "بثينة") {

                document.getElementById("message").innerHTML =
                "بثينة ❤️ شكراً من قلبي على كلش، على وقفتك معايا واهتمامك بيا. وجودك في حياتي حاجة نقدرها بزاف 🥹❤️";

            } else {

                document.getElementById("message").innerHTML =
                "هممم 🤔 جربي اكتبي اسمك الصحيح ❤️";

            }
        }

    </script>

</body>
</html>