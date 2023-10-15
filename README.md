<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Bot Name</title>
    <style>
        body {
            background-color: #8637f4;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #8637f4;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            color: white;
        }
        .container {
            background-color: white;
            border-radius: 10px;
            margin: 20px;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        .button-container {
            text-align: center;
        }
        .button {
            background-color: black;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            text-decoration: none;
            margin: 10px;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #8637f4;
        }
        .section {
            padding: 20px;
        }
        .section a {
            color: black;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Your Bot Name</h1>
        <div class="button-container">
            <a href="#introduction" class="button">Introduction</a>
            <a href="#tos" class="button">Terms of Service</a>
            <a href="https://discord.gg/support-server" class="button">Support Server</a>
            <a href="https://discordapp.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot&permissions=YOUR_PERMISSIONS" class="button">Invite Bot</a>
        </div>
    </div>

    <div class="container">
        <img src="bot-icon.png" alt="Bot Icon" style="display: block; margin: 0 auto;">
        <div id="introduction" class="section">
            <h2>Introduction</h2>
            <p>Your bot introduction goes here.</p>
        </div>

        <div id="tos" class="section">
            <h2>Terms of Service</h2>
            <p>Your bot's terms of service go here.</p>
        </div>
    </div>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
