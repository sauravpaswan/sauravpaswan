<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SauravX Bots - Get Your Own WhatsApp Bot Today!</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: url('https://source.unsplash.com/1600x900/?mountain,clouds') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            position: relative;
            flex-direction: column;
        }

        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
        }

        .container {
            position: relative;
            z-index: 1;
            background: rgba(255, 255, 255, 0.1);
            padding: 40px;
            border-radius: 10px;
            backdrop-filter: blur(10px);
            width: 90%;
            max-width: 500px;
        }

        h1 {
            font-size: 30px;
            margin-bottom: 20px;
            animation: fadeIn 2s;
        }

        .pricing {
            background: rgba(0, 0, 0, 0.7);
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .pricing h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .pricing p {
            font-size: 18px;
            margin: 5px 0;
        }

        .btn {
            display: block;
            width: 80%;
            margin: 15px auto;
            padding: 15px;
            color: white;
            background: linear-gradient(45deg, #28a745, #218838);
            border: none;
            border-radius: 5px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: linear-gradient(45deg, #218838, #1e7e34);
            transform: scale(1.05);
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .whatsapp-logo {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            cursor: pointer;
            transition: transform 0.3s ease-in-out;
        }

        .whatsapp-logo:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="overlay"></div>

    <div class="container">
        <h1>Welcome to SauravX Bots!</h1>

        <!-- Pricing Details -->
        <div class="pricing">
            <h2>Pricing Details</h2>
            <p>📌 1 WhatsApp Bot - ₹1500 (for 3 months)</p>
            <p>📌 2 WhatsApp Bots - ₹2400 (for 3 months)</p>
        </div>

        <!-- WhatsApp Buttons -->
        <a class="btn" onclick="sendMessage('I want a WhatsApp Bot')">Get WhatsApp Bot</a>
        <a class="btn" onclick="sendMessage('I want pricing details')">Pricing Details</a>
        <a class="btn" onclick="sendMessage('I need customer support')">Customer Support</a>
    </div>

    <!-- WhatsApp Floating Logo -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" class="whatsapp-logo" onclick="window.location.href='https://wa.me/7559347682'">

    <script>
        function sendMessage(message) {
            window.location.href = `https://wa.me/7559347682?text=${encodeURIComponent(message)}`;
        }
    </script>
</body>
</html>
