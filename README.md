
## Be My Valentine Interactive Card

An interactive Valentine's Day webpage with smooth animations, sound effects, playful interactions, and a confetti celebration. Perfect for sharing with someone special!

## Preview

Open locally or via a shareable link to experience the full interaction, including animations and sound effects.

## Features

Animated gradient background

Card entrance and heartbeat animation

“No” button that moves on hover

Confetti animation on acceptance

Sound effects

Floating hearts animation

Responsive design

## Project Structure
```
.
├── main.html
└── README.md
```

## Running Locally

### Prerequisites
- Python 3 (usually pre-installed on macOS/Linux, available for Windows)

### Steps

1. **Open a terminal** in the project folder where `main.html` is located
2. **Start a local server**:
   ```bash
   python -m http.server 8000
   ```
3. **Find your local URL**: The terminal will confirm the server is running. Open your browser and visit:
   ```
   http://localhost:8000/main.html
   ```
   
   > **Note**: The exact URL depends on your port number (8000 in this case). If port 8000 is already in use, Python will use a different port—check your terminal output for the exact URL. It will show something like `Serving HTTP on [::]:PORT_NUMBER`

## Customization

### Change the Valentine's Name

1. Open `main.html` in a text editor
2. Search for `(name)` (you'll find it in the card heading)
3. Replace `(name)` with your Valentine's actual name:
   ```html
   <h2>Alex,<br>will you be my Valentine?</h2>
   ```
4. Save the file and refresh your browser

### Add a Personalized Message or Nickname

Find the same `<h2>` tag and customize it further:
```html
<h2>My Love 💕,<br>will you be my Valentine?</h2>
```

Save and refresh to see your changes!

## Sharing the Page Using ngrok

Turn your local server into a shareable public link with ngrok.

### Setup ngrok

1. Download and install ngrok from [ngrok.com](https://ngrok.com)
2. Create a free account and authenticate (follow the setup instructions)
3. Keep your terminal window open where your Python server is running

### Generate a Shareable URL

Open a **new terminal window** and run:
```bash
ngrok http 8000
```

ngrok will output a temporary public URL (e.g., `https://abc123.ngrok.io`). Share this URL with your Valentine!

> **Important**: The URL changes each time you restart ngrok. Your local server must keep running for the link to work.

# Notes

- **ngrok URL is temporary**: It regenerates each time you restart the service. Keep your local server running while sharing.
- **Audio requires interaction**: Most browsers block audio playback until the user interacts with the page (this is normal browser behavior).
- **Best browsers**: Chrome, Edge, or Firefox (for full animation and sound support).
- **Offline use**: You can also just open `main.html` directly in your browser- no server needed if sharing isn't necessary.

## License

This project is for personal and educational use.
Feel free to customize and share responsibly.
