<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Divine Stack™ Pre-Order</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        h1 {
            color: #d4af37;
        }
        p {
            color: #555;
        }
        .price {
            font-size: 24px;
            font-weight: bold;
            margin: 20px 0;
        }
        button {
            background-color: #d4af37;
            color: #fff;
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #b08e2e;
        }
        .countdown {
            font-size: 18px;
            color: #d4af37;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>The Divine Stack™ Cookie Pre-Order</h1>
        <p>**The Thickest, Most Luxurious Cookie On Earth.**</p>
        <p>🔥 $15 per cookie or $60 for a 4-pack.</p>
        <p>👉 Pre-Orders Close Every Friday.</p>
        <p class="price">Reserve Your Box Now</p>
        <button onclick="orderNow()">Pre-Order Now</button>
        <p class="countdown" id="countdown"></p>
    </div>

    <script>
        function orderNow() {
            window.location.href = "https://cash.app/$YourCashApp";
        }

        // Countdown Timer
        var countDownDate = new Date("Mar 10, 2025 18:00:00").getTime();
        var x = setInterval(function() {
            var now = new Date().getTime();
            var distance = countDownDate - now;

            var days = Math.floor(distance / (1000 * 60 * 60 * 24));
            var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            var seconds = Math.floor((distance % (1000 * 60)) / 1000);

            document.getElementById("countdown").innerHTML = "Pre-Orders Close In: " + days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

            if (distance < 0) {
                clearInterval(x);
                document.getElementById("countdown").innerHTML = "Pre-Orders Are Now Closed.";
            }
        }, 1000);
    </script>
</body>
</html>
