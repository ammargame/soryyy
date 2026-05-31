<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorry Sama Madam Ji ❤️</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .card {
            background: white;
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            max-width: 550px;
        }

        h1 {
            color: #ff4d6d;
        }

        p {
            font-size: 20px;
            color: #333;
        }

        button {
            background: #ff4d6d;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 18px;
        }

        button:hover {
            background: #e63956;
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>🙏 Sorry Sama Madam Jiii ❤️</h1>

        <p>
            Dear Sama Madam Jiii,<br><br>
            I know you're angry with me 😔.<br>
            I'm really sorry for my mistake.<br>
            Please forgive me and give me one more chance ❤️🥺
        </p>

        <button onclick="openSorryPage()">Click Here ❤️</button>
    </div>

    <script>
        function openSorryPage() {

            let newWindow = window.open("", "_blank");

            let sorryText = "";

            for (let i = 1; i <= 100; i++) {
                sorryText += i + ". Sorry Sama Madam Jiii ❤️🥺🙏<br>";
            }

            newWindow.document.write(`
                <!DOCTYPE html>
                <html>
                <head>
                    <title>100 Times Sorry ❤️</title>

                    <style>
                        body{
                            font-family: Arial, sans-serif;
                            text-align:center;
                            background: linear-gradient(135deg,#ffdde1,#ee9ca7);
                            padding:30px;
                        }

                        h1{
                            color:#d90429;
                        }

                        .sorry{
                            font-size:22px;
                            line-height:1.8;
                            background:white;
                            padding:20px;
                            border-radius:15px;
                            max-width:700px;
                            margin:auto;
                            box-shadow:0 5px 15px rgba(0,0,0,0.2);
                        }

                        button{
                            margin-top:30px;
                            background:#ff4d6d;
                            color:white;
                            border:none;
                            padding:12px 25px;
                            border-radius:10px;
                            cursor:pointer;
                            font-size:18px;
                        }

                        button:hover{
                            background:#e63956;
                        }
                    </style>
                </head>

                <body>

                    <h1>🙏 100 Times Sorry Sama Madam Jiii ❤️ 🙏</h1>

                    <div class="sorry">
                        ${sorryText}
                    </div>

                    <button onclick="showPromise()">
                        Click Here Again ❤️
                    </button>

                    <script>
                        function showPromise(){

                            document.body.innerHTML = \`
                                <div style="
                                    max-width:700px;
                                    margin:80px auto;
                                    background:white;
                                    padding:40px;
                                    border-radius:20px;
                                    box-shadow:0 5px 20px rgba(0,0,0,0.2);
                                ">
                                    <h1 style="color:#ff4d6d;">
                                        🎂 A Promise For You ❤️
                                    </h1>

                                    <h2 style="color:#333; line-height:1.8;">
                                        Sama Madam Jiii ❤️<br><br>

                                        I will never forget your birthday again 🎂❤️<br><br>

                                        You are very special to me 🥺❤️<br><br>

                                        Please forgive me 🙏❤️
                                    </h2>

                                    <h1>
                                        ❤️🌹🥺🙏🎂❤️
                                    </h1>
                                </div>
                            \`;
                        }
                    <\/script>

                </body>
                </html>
            `);
        }
    </script>

</body>
</html>
