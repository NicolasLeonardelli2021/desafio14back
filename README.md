 "dependencies": {
    "bcrypt": "^5.0.1",
    "connect-mongo": "^4.6.0",
    "cookie-parser": "^1.4.6",
    "cors": "^2.8.5",
    "dotenv": "^16.0.0",
    "ejs": "^3.1.7",
    "express": "^4.18.1",
    "express-session": "^1.17.2",
    "faker": "^5.5.3",
    "moment": "^2.29.3",
    "mongoose": "^6.3.2",
    "passport": "^0.5.2",
    "passport-facebook": "^3.0.0",
    "session-file-store": "^1.5.0",
    "socket.io": "^4.5.0",
    "yargs": "^17.5.1"
  },
  "devDependencies": {
    "nodemon": "^2.0.16"
  }
}

"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "nodemon mongo.js",
    "start": "node mongo.js"
  }
