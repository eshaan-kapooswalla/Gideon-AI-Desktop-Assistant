
        body {
            background-color: #f0f8ff;
            font-family: 'Comic Sans MS', sans-serif;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #ff4500;
            text-align: center;
            font-size: 3em;
        }
        h2 {
            color: #1e90ff;
            font-size: 2em;
        }
        p {
            font-size: 1.2em;
            line-height: 1.5;
        }
        .highlight {
            color: #32cd32;
            font-weight: bold;
        }
        .command {
            background-color: #ffe4b5;
            border-left: 5px solid #ff6347;
            padding: 10px;
            margin: 10px 0;
            font-family: monospace;
        }
        .fun-text {
            color: #9400d3;
            font-size: 1.5em;
        }
        a {
            color: #1e90ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <h1>🤖 Welcome to Gideon AI! 🎉</h1>

    <p>Say hello to <span class="highlight">Gideon</span> — your brand-new AI assistant! This project brings you an interactive, voice-activated AI that listens to your commands, opens websites, plays music, tells you the time, and even holds a chat! 🔥</p>

    <h2>How to get started?</h2>
    <p>First, make sure you have all the necessary dependencies installed:</p>
    <div class="command">
        pip install speechrecognition openai
    </div>
    
    <p>Don't forget to add your OpenAI API key to the <span class="highlight">config.py</span> file! 😉</p>

    <h2>Features of Gideon AI 🌟</h2>
    <ul>
        <li>🎤 <strong>Voice Commands</strong>: Speak to Gideon and it will recognize your commands using <span class="highlight">Google Speech Recognition</span>!</li>
        <li>🌐 <strong>Web Browsing</strong>: Ask Gideon to open websites like YouTube, Wikipedia, and Google.</li>
        <li>🎵 <strong>Play Music</strong>: Just say "open music" and it'll play your favorite track (make sure to set the correct music path!).</li>
        <li>🕒 <strong>Tell Time</strong>: Wondering what time it is? Just ask Gideon!</li>
        <li>💬 <strong>Chat with AI</strong>: Gideon uses OpenAI to chat with you! Have fun and ask anything.</li>
    </ul>

    <h2>How to Use?</h2>
    <p>Run the program and get ready to speak! Here are some cool things you can say:</p>
    <ul>
        <li><span class="fun-text">"Open YouTube!"</span></li>
        <li><span class="fun-text">"What's the time?"</span></li>
        <li><span class="fun-text">"Using artificial intelligence, tell me something interesting."</span></li>
    </ul>

    <p>And if you're feeling talkative, just start chatting! Gideon will respond to all your queries with some AI magic. ✨</p>

    <h2>Exit the Program</h2>
    <p>To gracefully exit, just say:</p>
    <div class="command">
        "Gideon Quit"
    </div>

    <h2>Reset Chat</h2>
    <p>Want to start fresh? Reset the conversation by saying:</p>
    <div class="command">
        "Reset chat"
    </div>

    <h2>Need Help?</h2>
    <p>If you have any questions or suggestions, feel free to <a href="mailto:support@gideonai.com">reach out</a>! 💌</p>

    <h2>Enjoy! 🚀</h2>
    <p>We hope you have an awesome time using Gideon AI. Get creative and make it your own. Let's build something cool together! 😎</p>

</body>
</html>
