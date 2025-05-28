# online-pocker
This is a real-time online poker prototype built with React, Node.js, and Socket.io.  
Players can join rooms, start a game, receive private hands and see shared table cards in real-time.

##  What it can do:

- Join a custom room (just give it a name)
- See who else is in the room
- Click Start Game to begin
- You’ll get 2 personal cards
- Watch the table fill up: Flop, Turn, River
- Everyone stays in sync — no refresh needed!
  
 ##  Tech Stack

- Frontend: React + Vite
- Backend: Node.js, Express, Socket.io
- Real-time logic via WebSocket (Socket.IO)
- Basic state management via useState and useEffect
  
##  Installation
```bash
git clone https://github.com/melash/online-pocker.git
cd online-pocker

# Backend
cd server
npm install
node index.js

# Frontend (in a new tab)
cd ../client
npm install
npm run dev

---

This project was built as part of my application to an incubator.  
It's my first multiplayer real-time game — and I coded everything by hand from scratch.

Made with 🤍 by Aisha(Mels)
