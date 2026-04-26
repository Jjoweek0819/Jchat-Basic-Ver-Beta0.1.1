# JChat-Pro

JChat-Pro is a Python-based multi-room communication tool designed for seamless interaction. It integrates classic instant messaging with real-time voice transmission using a robust dual-protocol architecture.

---

### 🛠 Project Overview
The project is built on three core pillars:
* **Main Server:** A Flask-SocketIO backend managing authentication, JSON-based message history, and file transfers.
* **Voice Server:** A high-performance UDP script dedicated to low-latency audio broadcasting.
* **Client Application:** A modern desktop UI built with **PyQt6**, ensuring a smooth user experience.

---

### ✨ Core Functionalities
* **Group Chatting:** Create or join multiple rooms to exchange text and emojis.
* **Voice Integration:** Real-time voice streaming via **PyAudio** over UDP for instant communication.
* **Media Handling:** Share images and videos (up to 8MB) with a built-in player and previewer.
* **Message Pinning:** Keep important information visible at the top of the chat.
* **Custom Profiles:** Personalize your presence with custom avatars and settings.

---

### 🔧 Technical Implementation
* **Hybrid Networking:** Leverages **TCP (SocketIO)** for reliable data and **UDP** for lightning-fast voice packets.
* **Multi-threading:** Independent background threads handle voice and socket listeners, keeping the UI responsive.
* **Lightweight Storage:** Uses a structured **JSON file system** for easy data management without the overhead of complex databases.

---

### 🚀 Getting Started
1. Install dependencies: `pip install flask-socketio pyqt6 pyaudio`
2. Run the Main Server & Voice Server.
3. Launch the Client Application.
