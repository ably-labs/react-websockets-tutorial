The accompanying source code for our tutorial and video tutorial on how to use WebSockets with React and Node.

- 📝 Read the complete guide to WebSockest with React (including tutorial) [here](https://ably.com/blog/websockets-react-tutorial#how-to-use-web-sockets-with-react-and-node) and follow along.
- 📹 Alternatively, we recorded the same tutorial as a video [here](https://youtu.be/4Uwq0xB30JE).

In the tutorial, we build an realtime multiplayer cursor feature using [React useWebSocket](https://github.com/robtaussig/react-use-websocket) and [perfect-cursors](https://github.com/steveruizok/perfect-cursors) on the frontend, and [ws](https://github.com/websockets/ws) on the back.

The final product looks like this:

![Live cursors demo](./media/demo.gif)

Follow along using your preferred tutorial medium above, browse and learn from the code here on GitHub, or get hands-on and run the demo by following the instructions included below.

## Running the demo
Want to run the demo and check it out? No problem!

First, download the repository with Git:

```
git clone https://github.com/ably-labs/react-websockets-tutorial
cd react-websockets-tutorial
```

To run the server, run:

```
cd server
npm install
npm run
```

To run the client simultaneously, open a new terminal shell, and run:

```
cd client
npm install
npm run dev
```