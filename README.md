<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaba.crochet - Handmade Torebki & Plecaki</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8e8d0;
            color: #333;
        }
        header {
            background-color: #d08c60;
            padding: 20px;
            text-align: center;
            color: white;
            font-size: 24px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 15px;
            margin-bottom: 20px;
            background-color: white;
        }
        button {
            background-color: #d08c60;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
        .reviews {
            margin-top: 20px;
            padding: 10px;
            background-color: #f4d6a3;
        }
        .login-form {
            background: white;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
            max-width: 300px;
            margin: 20px auto;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .login-form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <header>Gaba.crochet - Handmade Torebki & Plecaki</header>
    <div class="container">
        <div class="login-form">
            <h2>Zaloguj się</h2>
            <input type="text" placeholder="Nazwa użytkownika" id="username">
            <input type="password" placeholder="Hasło" id="password">
            <button onclick="login()">Zaloguj</button>
        </div>
        <div class="product">
            <h2>Torebka Handmade</h2>
            <p>Piękna, ręcznie robiona torebka z wysokiej jakości włóczki.</p>
            <button onclick="alert('Dodano do koszyka!')">Zamów</button>
            <div class="reviews">
                <h3>Opinie:</h3>
                <p>⭐️⭐️⭐️⭐️⭐️ - Świetna jakość! - Kasia</p>
                <p>⭐️⭐️⭐️⭐️⭐️ - Przepiękne wykonanie! - Anna</p>
            </div>
        </div>
    </div>
    <script>
        function login() {
            let username = document.getElementById("username").value;
            let password = document.getElementById("password").value;
            if(username === "admin" && password === "1234") {
                alert("Zalogowano pomyślnie!");
            } else {
                alert("Błędna nazwa użytkownika lub hasło");
            }
        }
    </script>
</body>
</html>
