<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SauravX Bots - Get Your Own WhatsApp Bot Today!</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Welcome to SauravX Bots</h1>
        <p>Get your own WhatsApp bot today and automate your business.</p>
        
        <div class="buttons">
            <a href="https://wa.me/7559347682?text=I'm%20interested%20in%20a%20WhatsApp%20Bot" class="btn">WhatsApp Bot</a>
            <a href="https://wa.me/7559347682?text=I%20want%20to%20know%20the%20pricing%20details" class="btn">Pricing Info</a>
            <a href="https://wa.me/7559347682?text=I%20need%20customer%20support" class="btn">Customer Support</a>
        </div>
    </div>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/7559347682" class="whatsapp-float" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
    </a>
</body>
</html>
/* Google Font */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

body {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    text-align: center;
    background: url('https://source.unsplash.com/1600x900/?mountains,nature') no-repeat center center/cover;
    color: white;
}

.container {
    padding: 100px 20px;
    background: rgba(0, 0, 0, 0.5);
    border-radius: 10px;
    width: 80%;
    margin: auto;
}

h1 {
    font-size: 36px;
    font-weight: 600;
    margin-bottom: 10px;
    animation: fadeIn 2s;
}

p {
    font-size: 18px;
    margin-bottom: 20px;
    animation: fadeIn 3s;
}

.buttons {
    display: flex;
    justify-content: center;
    gap: 15px;
}

.btn {
    text-decoration: none;
    color: white;
    background: #25D366;
    padding: 12px 24px;
    font-size: 18px;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background: #128C7E;
}

/* WhatsApp Floating Button */
.whatsapp-float {
    position: fixed;
    bottom: 20px;
    right: 20px;
    width: 60px;
}

.whatsapp-float img {
    width: 100%;
    border-radius: 50%;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}
