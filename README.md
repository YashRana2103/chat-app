# Snappy - Chat Application

Snappy is chat application build with the power of MERN Stack. You can find the tutorial [here](https://www.youtube.com/watch?v=otaQKODEUFs)

![login page](./images/snappy_login.png)

![home page](./images/snappy.png)

## Installation Guide

### Requirements

- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

### Installation

#### First Method

```shell
git clone https://github.com/YashRana2103/chat-app.git
cd chat-app
```

Now rename env files from .env.example to .env

```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies

```shell
cd server
yarn
cd ..
cd public
yarn
```

We are almost done, Now just start the development server.

For Frontend.

```shell
cd public
yarn start //or npm start
```

For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.

```shell
cd server
yarn start //or npm start
```

Done! Now open [http://localhost:3000](http://localhost:3000) in your browser.