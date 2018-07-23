# Chat Application

This project is build using Node.js Express.js Sentry.io Redis Socket.io

## How to install
1. clone this repository `git clone https://github.com/nhunhea/chat-nodejs-sentry-redis-socketio.git`
2. then `cd chat-nodejs-sentry-redis-socketio.git`
3. then `npm install`
4. Create file `creds.json` and get configuration from RedisLabs
```
{
    "user": "",
    "password": "",
    "host": "",
    "port": 
}
```
5. Create raven.env and get configuration from Sentry.io
6. then type `source ./raven.env` on terminal 
7. then type `npm start`
8. And access from browser on `http://localhost:8080/`
9. Or you can visit the deployment app on `https://hidden-bastion-81589.herokuapp.com`