## Quickstart

1. Clone Repo
2. cd && npm i
3. From the root directory:
   3.1 npm run dev (start vite client)
   3.2 node src/server/index.js (start server)

## Motivation

Is it possible to render a 3D scene serverside and stream it to a client? The answer is: Yes. It is possible to stream a three.js scene using a websockets (specifically UDP websockets via Geckos.io), and node.js implementations of the canvas and webrtc.

Potential applications include:

- Game Streaming
- CAD Streaming
