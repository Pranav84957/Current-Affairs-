<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Current Affairs Chatbot</title>
    <link rel="stylesheet" href="https://cdn.botpress.cloud/webchat/v3.1/shareable.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }

        #chatbot {
            width: 400px;
            height: 600px;
            border: 1px solid #ccc;
            border-radius: 8px;
            overflow: hidden;
        }
    </style>
</head>

<body>

    <div id="chatbot"></div>

    <script src="https://cdn.botpress.cloud/webchat/v3.1/webchat.js"></script>
    <script>
        window.botpressWebChat.init({
            host: 'https://cdn.botpress.cloud/webchat/v3.1',
            botId: 'your-bot-id', // Replace with your actual bot ID
            configUrl: 'https://files.bpcontent.cloud/2025/07/19/08/20250719082903-0PN0N4YO.json'
        });
    </script>

</body>

</html>
