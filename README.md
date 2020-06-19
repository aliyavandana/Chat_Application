# Chat_Application
 Real Time Chat Application using REACTJS,SOCKETS,NODEJS

Real Time Chat Application using ReactJS ,socket.io and NodeJS

Create 2 folders client and server.

In Client,

Run : create-react-app ./

//creates app inside client folder

//To Install all the Dependencies on Client Side

Run: npm install --save react-router socket.io-client react-scroll-to-bottom react-emoji query-string

In Server,

//To Install package.json on server side

Run: npm init -y

//To Install all the Dependencies on Server Side

Run: npm install --save cors nodemon express socket.io

//Cors useful during production

In Server-package.json

//Add in scripts

'start' : 'nodemon index.js'

//Basically it runs the server continously, we don't need to run node index.js everytime,it does that for us.
