
# Socket.IO Chat

A simple chat demo for socket.io

<img width="1194" alt="screen shot 2018-05-26 at 7 59 34 pm" src="https://user-images.githubusercontent.com/20756728/40581155-47c9940e-611f-11e8-9156-5971a69b0417.png">
<img width="1280" alt="screen shot 2018-05-26 at 8 01 05 pm" src="https://user-images.githubusercontent.com/20756728/40581174-980133dc-611f-11e8-806d-d8738214ef84.png">
<img width="1280" alt="screen shot 2018-05-26 at 8 01 34 pm" src="https://user-images.githubusercontent.com/20756728/40581175-980e856e-611f-11e8-8374-b3f46d19e17b.png">

## How to use

```
$ npm install
$ npm install --save express
$ npm install --save socket.io
$ npm start
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves
the chatroom.
