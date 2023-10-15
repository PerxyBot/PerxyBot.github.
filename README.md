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
            cursor: pointer;
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
        .dropdown {
            position: relative;
            display: inline-block;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: white;
            min-width: 160px;
            border-radius: 10px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
            text-align: left;
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }
        .button {
            background-color: black;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            text-decoration: none;
            margin: 10px;
            transition: background-color 0.3s ease;
            display: inline-block;
        }
        .button:hover {
            background-color: #8637f4;
        }
        .section {
            padding: 20px;
        }
        .rating {
            font-size: 24px;
        }
        .features {
            margin: 20px 0;
        }
        .feature {
            display: flex;
            align-items: center;
            margin: 10px 0;
        }
        .feature-icon {
            font-size: 24px;
            margin-right: 10px;
        }
        .feature-text {
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Your Bot Name</h1>
        <div class="button-container">
            <div class="dropdown">
                <button class="button">Menu &#9660;</button>
                <div class="dropdown-content">
                    <a href="https://discord.gg/support-server" target="_blank">Support Server</a>
                    <a href="https://example.com" target="_blank">Website</a>
                </div>
            </div>
        </div>
    </div>

    <div class="container">
        <img src="bot-icon.png" alt="Bot Icon" style="display: block; margin: 0 auto;">
        <div id="introduction" class="section">
            <h2>Introduction</h2>
            <p>Your bot introduction goes here.</p>
            <div class="rating">
                &#9733;&#9733;&#9733;&#9733;&#9733;
            </div>
        </div>
        
        <div class="section features">
            <h2>Features</h2>
            <div class="feature">
                <div class="feature-icon">&#10003;</div>
                <div class="feature-text">Feature 1: Description of feature 1.</div>
            </div>
            <div class="feature">
                <div class="feature-icon">&#10003;</div>
                <div class="feature-text">Feature 2: Description of feature 2.</div>
            </div>
            <div class="feature">
                <div class="feature-icon">&#10003;</div>
                <div class="feature-text">Feature 3: Description of feature 3.</div>
            </div>
        </div>
    </div>
    
    <div class="button-container">
        <a href="https://discordapp.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot&permissions=YOUR_PERMISSIONS" class="button">Invite</a>
    </div>
</body>
</html>
