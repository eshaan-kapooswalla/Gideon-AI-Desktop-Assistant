Gideon AI - README
Welcome to Gideon AI! This project is an interactive, voice-activated AI assistant capable of recognizing voice commands, opening websites, playing music, telling the time, and even chatting using OpenAI.
Features
Voice Commands: Gideon listens to your voice using Google Speech Recognition and responds to various commands.
Web Browsing: Ask Gideon to open websites like YouTube, Wikipedia, or Google.
Music: Play a specific song by saying "Open Music." Ensure that the path to the music file is correctly set in the script.
Time Inquiry: Ask Gideon for the current time, and it will tell you.
AI Chat: Have a conversation with Gideon! It uses OpenAI to respond to your queries intelligently.
Usage Instructions
Run the program, and start speaking once it's ready to listen.

Some example commands you can give:

"Open YouTube"
"What's the time?"
"Using artificial intelligence, tell me something interesting."
To have a casual conversation with Gideon, just start speaking or typing, and the AI will respond!

Exit the Program: To quit Gideon, say: "Gideon Quit".

Reset the Chat: To reset the conversation, say: "Reset chat".

Configuration
Make sure you update the following paths in the code to match your system:

Music Path: Modify the path for the song in the line with "open music"
Requirements
Python 3.x
Required Python libraries:
speechrecognition
openai
webbrowser
datetime
numpy
How It Works
Gideon listens for voice commands using your system's microphone.
It processes those commands using Google’s Speech Recognition API.
Based on the command, Gideon can either:
Open a specific website (like YouTube, Google, etc.),
Play a song from a pre-configured path,
Tell you the time, or
Chat with you using OpenAI's GPT model.
License
This project is for personal use. Feel free to modify and improve it as you see fit.

