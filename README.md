# react-native-pusher-chat

This project shows a full React Native chat app ready to be deployed onto Android or iOS, complete with the server component.

View tutorial

Getting Started
In order to use this you need to register with http://pusher.com and to add a pusher.json file to both the server and client directories. This file should look like:

{
    "appId":"SOME_APP_ID",
    "key":"SOME_APP_KEY",
    "secret":"SOME_APP_SECRET",
    "cluster":"eu",
    "encrypted":true,
    "restServer":"http://192.168.0.15:4000"
}

Note that the restServer property needs to point to the Server component when it is running, and is only needed in the client version of the file.

Running the server
The server can be built by executing "npm install" inside the server directory. The server can then be run by executing "node index.js" from the same directory. By default this starts on port 4000.

Running the client
The client can be built by executing "npm install" inside the client directory. The client can then be run by executing "npm start" inside the same directory and following the on-screen prompts to access it from your mobile device.
