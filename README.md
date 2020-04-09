# socket.io-demo
socket.io demo

### Set Up

Run:
```sh
npm install
```

### Usage

1. Run the server with:
```sh
npm start
```
2. Open http://localhost:3000 in a browser window.
3. Open http://localhost:3000 in another browser window.
4. Start chatting.
5. Stop the server with CTRL+C when finished.

### To Do:

- Broadcast a message to connected users when someone connects or disconnects.
- Add support for nicknames.
- Don’t send the same message to the user that sent it himself. Instead, append the message directly as soon as he presses enter.
- Add “{user} is typing” functionality.
- Show who’s online.
- Add private messaging.