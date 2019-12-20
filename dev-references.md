## Node packages to Investigate
https://www.npmjs.com/package/socket.io
https://www.npmjs.com/package/socket.io-client
https://www.npmjs.com/package/planck-js

## Game Programming
http://gameprogrammingpatterns.com/game-loop.html
- 'Game Loop' design pattern overview/considerations

https://www.youtube.com/watch?v=h47zZrqjgLc
- [GDC] Halo Reach (latency) networking case study

http://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html
- 'Client-side prediction' & 'Server reconciliation'
- [Live Demo] http://www.gabrielgambetta.com/client-side-prediction-live-demo.html
-> https://developer.valvesoftware.com/wiki/Latency_Compensating_Methods_in_Client/Server_In-game_Protocol_Design_and_Optimization
   - Lag compensation post by Valve
-> http://www.kinematicsoup.com/news/2017/5/30/multiplayerprediction
   - 'Converging prediction' algorithm

https://www.html5rocks.com/en/tutorials/canvas/notearsgame/
- HTML5 canvas game set-up walkthrough

https://hackernoon.com/how-to-build-a-multiplayer-browser-game-4a793818c29b
- HTML5 canvas game set-up walkthrough 

## Client Side
https://www.tutorialspoint.com/expressjs/expressjs_static_files.htm
- Serving static files via express

https://github.com/socketio/socket.io-client#how-to-use
- Set-up browser-side Socket.io connection to backend Node.js server

## Server Side
https://github.com/socketio/socket.io#standalone
- Integrate Socket.io server connection endpoint into game loop
- Server will be standalone Node.js; acting exclusively as a websockets (Socket.io) server

[Future Goal] Custom defined 'load balancing' service which routes initial (Socket.io) connection accordingly
