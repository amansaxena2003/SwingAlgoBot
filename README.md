<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SwingAlgoBot - Stock Picks & Analysis</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #060606;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        .stock-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            margin-bottom: 1rem;
            background-color: #e8e8e8;
        }
        .stock-card img {
            max-width: 100%;
            border-radius: 8px;
        }
        .subscribe-section {
            border-top: 2px solid #eee;
            margin-top: 2rem;
            padding-top: 2rem;
        }
        .subscribe-section img {
            max-width: 200px;
            border-radius: 10px;
            margin-top: 1rem;
        }
        footer {
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
            background-color: #dfdddd;
            font-size: 0.9rem;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #060607;
            color: white;
            border-radius: 5px;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>📊 SwingAlgoBot</h1>
        <p>Get premium swing trade stock picks daily</p>
    </header>

    <div class="container">
        <h2>Today's Stock Picks</h2>

        <div class="stock-card">
            <h3>RITCO</h3>
            <p>📈 Buy @ ₹320 | SL ₹300 | Target ₹365</p>
            <img src="https://www.tradingview.com/x/eJDviNao/" alt="RITCO Chart">
        </div>

        <div class="stock-card">
            <h3>CARBORUNDUM UNIVERSAL</h3>
            <p>📈 Buy @ ₹1010 | SL ₹965 | Target ₹1140</p>
            <img src="https://www.tradingview.com/x/MH0baUXg/" alt="CUMI Chart">
        </div>

        <div class="stock-card">
            <h3>ASAHI SONGWON</h3>
            <p>📈 Buy @ ₹455 | SL ₹432 | Target ₹510</p>
            <img src="https://www.tradingview.com/x/e7brBuHk/" alt="Asahi Chart">
        </div>

        <!-- ✅ Subscription Section -->
        <div class="subscribe-section">
            <h2>🔒 Unlock Premium Picks</h2>
            <p>💳 To get full access, subscribe for just ₹199/week.</p>
            <p><strong>📍 UPI ID:</strong> <code>amansaxenaa@yesg</code></p>
            <img src="https://i.postimg.cc/28WvhMR5/6339011686538791070.jpg" alt="UPI QR Code">
            <p><a class="btn" href="https://t.me/amansaxenaa">📩 Send Payment Screenshot</a></p>
        </div>
    </div>

    <footer>
        &copy; 2025 SwingAlgoBot.com | Powered by Telegram Bot
    </footer>
</body>
</html>
