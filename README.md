
#Be My Valentine Interactive Card

An interactive Valentine’s Day webpage built with HTML, CSS, and JavaScript.

It features smooth animations, sound effects, a playful “No” button, and a confetti celebration when “Yes” is clicked. Designed to be shared with someone special.

Preview

Open locally or via a shareable link to experience the full interaction, including animations and sound effects.

Features

Animated gradient background

Card entrance and heartbeat animation

“No” button that moves on hover

Confetti animation on acceptance

Sound effects

Floating hearts animation

Responsive design

Project Structure
.
├── index.html
└── README.md

Running Locally

Ensure Python is installed

Open a terminal in the project directory

Start a local server:

python -m http.server 8000


Open your browser and visit:

http://localhost:8000/index.html

Customization
Change the Valentine’s Name

Line 173
Replace (name) with your Valentine’s name:

<h2>Alex,<br>will you be my Valentine?</h2>

Add a Personalized Message or Nickname

Line 180
Edit the text to include a nickname or custom message:

<h2>Alex 💕,<br>will you be my Valentine?</h2>

Sharing the Page Using ngrok

You can create a temporary public URL using ngrok.

Set Up ngrok

Download ngrok

Create an account

Generate an authentication token

Add the token to ngrok following the official setup instructions

Start the Local Server
python -m http.server 8000

Generate a Shareable URL
Windows PowerShell
ngrok http://localhost:8000

macOS or Linux
ngrok http 8000


ngrok will output a temporary public URL that you can share.

Notes

The ngrok URL changes each time the service is restarted

Audio playback requires user interaction due to browser policies

Best viewed in modern browsers such as Chrome, Edge, or Firefox

License

This project is for personal and educational use.
Feel free to customize and share responsibly.
