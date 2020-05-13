# Socket.io and React Js Chat Applicattion | With a NodeJs/Express Backend API

### About:

Chat app  built using React (React on the frontend) and NodeJS/Express/Socket.io Backend.

Users are able to join a chat room and message other users in real-time.

### Tech Stack:

* NodeJS/Express
* SOCKET.IO
* React (Create React App)
* React Router 4
* Moment JS
* SASS

### Screenshot

<p align="center">
    <img src="http://git-assets.react-starter-kit.com/react_chat_app.png">  
</p>

## How to run the app

Before proceeding, please ensure you have the following software installed on your computer.

* Docker
* Docker-compose
* Git

### Useful links

* Download Git CLT - Windows: https://git-scm.com/download/windows Mac: https://git-scm.com/download/mac

## Install Docker

## Linux installation

- curl https://get.docker.com | sudo bash

## add yourself to the docker group

- sudo usermod -aG docker $(whoami)

## Getting started

Please fork a copy of this repository. Forking a repository allows you to freely experiment with changes without affecting the original project. Alternatively download or clone the master branch.

### Download & Install Dependencies on your machine 

Clone the repo to your machine 

```
git clone <CloneURL>
```

### Lunch the backend

1)	Within terminal or cmd ensure you have navigated inside the 'Backend' directory and installed the dependencies

```
cd <../path/to/Backend> 
yarn install OR npm install
```

2) Run the start script

``` 
yarn run start OR npm run start
```

### Lunch the frontend

1) Open a new terminal window and navigate inside the 'Frontend' folder as you will need to keep the backend running in the background

```
cd <../path/to/Frontend> 
yarn install OR npm install
```

2) Run the start script

``` 
yarn run start OR npm run start
```

Your app should be running on: http://localhost:3000
