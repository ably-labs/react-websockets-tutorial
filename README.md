The accompanying source code for our tutorial and video tutorial on how to use WebSockets with React and Node.

- 📝 Read the written tutorial here and follow along.
- 📹 Alternatively, we recorded the same tutorial as a video [here](https://youtu.be/4Uwq0xB30JE).

In this tutorial, we build an realtime multiplayer cursor feature using [useWebSocket](https://github.com/robtaussig/react-use-websocket) WebSockets and [perfect-cursors](https://github.com/steveruizok/perfect-cursors). 

The final product looks something like this:

![Live cursors demo](./media/demo.gif)

Follow along using your preferred tutorial medium above, browse and learn from the code, or have some fun and run the demo using the instructions below.

## Running the demo
Want to run the demo and check it out? No problem!

First, download the repository with Git:

```
git clone https://github.com/ably-labs/react-websockets-tutorial
cs react-websockets-tutorial
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