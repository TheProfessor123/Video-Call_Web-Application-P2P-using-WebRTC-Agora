# Video Call Web Application (P2P using WebRTC & Agora)

A peer-to-peer video calling web application built using WebRTC and Agora RTM SDK for signaling.

## Features

- Real-time peer-to-peer video calls
- Camera control (turn on/off)
- Microphone control (mute/unmute) 
- Lobby system for creating/joining rooms
- Responsive design
- Auto-scaling video quality
- Support for modern browsers

## Tech Stack

- HTML/CSS/JavaScript
- WebRTC API
- [Agora RTM SDK](https://www.agora.io/en/products/real-time-messaging/)
- STUN servers (Google)

## Setup

1. Clone the repository:
```bash
git clone https://github.com/TheProfessor123/Video-Call_Web-Application-P2P-using-WebRTC-Agora.git
```

2. Replace the Agora App ID in main.js:
```javascript
let APP_ID = "YOUR_APP_ID_HERE"
```

## Usage

1. Open the application in a browser
2. You'll be redirected to the lobby if no room ID is specified
3. Create a new room or join an existing one
4. Allow camera and microphone permissions when prompted
5. Use the control buttons to:
   - Toggle camera
   - Toggle microphone
   - Leave call

## System Requirements

- Modern web browser with WebRTC support
- Camera and microphone
- Internet connection
- HTTPS for production deployment

## File Structure

```
├── agora-rtm-sdk-1.5.1.js
├── icons/
├── images/
├── index.html
├── lobby.css
├── lobby.html
├── main.css
└── main.js
```

## Development

For local development:

1. Set up a local web server
2. Create an Agora account and get an App ID
3. Update the APP_ID variable in main.js
4. Test with multiple browser windows/tabs

## License

This project uses the Agora RTM SDK which is licensed under the [Agora License Agreement](https://www.agora.io/en/sdk-license-agreement/).

## Credits

- [Agora.io](https://www.agora.io/) for the RTM SDK
- [WebRTC](https://webrtc.org/) for the peer-to-peer technology
- Google STUN servers
