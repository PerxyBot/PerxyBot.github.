<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Bot's Website</title>
    <style>
        body {
            background-color: purple;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background-color: #7289DA;
            padding: 20px;
        }

        header h1 {
            margin: 0;
        }

        nav {
            text-align: right;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 10px;
        }

        .button {
            background-color: #7289DA;
            color: white;
            border: none;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
            border-radius: 5px;
        }

        .section {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Your Bot's Name</h1>
            <nav>
                <a href="#introduction">Introduction</a>
                <a href="#tos">Terms of Service</a>
                <a class="button" href="https://discord.gg/your-support-server-invite-link" target="_blank">Support Server</a>
                <a class="button" href="https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot&permissions=YOUR_PERMISSIONS" target="_blank">Invite Bot</a>
            </nav>
        </div>
    </header>

    <div class="container">
        <section id="introduction" class="section">
            <h2>Introduction</h2>
            <p>Provide a detailed introduction to your Discord bot here.</p>
        </section>
        <section id="tos" class="section">
            <h2>Terms of Service</h2>
            <p>Include your terms of service here. Make sure to outline the rules and guidelines users must follow when using your bot.</p>
        </section>
    </div>
</body>
</html>
