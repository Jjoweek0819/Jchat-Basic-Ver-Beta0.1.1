# Jchat-Pro

Jchat-Pro is a simple multi-room chat application built with Python. It allows users to chat in different rooms and features a basic voice intercom function.

### ✨ Key Features
* **Multi-room Chat:** Join different rooms to send text messages and emojis.
* **Voice Chat:** A simple "Voice On/Off" toggle to talk with others in the same room (powered by UDP).
* **Media Sharing:** Send images and videos (up to 8MB). Includes a basic built-in player for quick viewing.
* **Pin Messages:** Keep important notes fixed at the top of the chat window.
* **Custom Profiles:** Set your own avatar and manage basic account settings.

### 🔧 How it Works
* **Backend:** Uses **Flask-SocketIO** for messaging and file transfers. Data is saved in simple **JSON files** (no complex database required).
* **Voice Engine:** A dedicated **UDP script** handles audio data for faster transmission.
* **Desktop UI:** Built with **PyQt6**, using multi-threading to keep the interface smooth while chatting or talking.

### 🚀 Quick Start
1. **Install dependencies:** `pip install flask-socketio pyqt6 pyaudio`
2. **Run the Servers:** Launch `server.py` and `voice_server.py`.
3. **Run the Client:** Launch `client.py` and start chatting!
