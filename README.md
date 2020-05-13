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

## Install Docker on Linux

- curl https://get.docker.com | sudo bash

### add yourself to the docker group

- sudo usermod -aG docker $(whoami)

## Install Docker-Compose

### Download Curl
- sudo apt install -y curl jq

### set which version to download (latest)
- version=$(curl -s https://api.github.com/repos/docker/compose/releases/latest | jq -r '.tag_name')

### download to /usr/local/bin/docker-compose
- sudo curl -L "https://github.com/docker/compose/releases/download/${version}/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

### make the file executable
- sudo chmod +x /usr/local/bin/docker-compose

## Getting started

### Download & Install Dependencies on your machine 

- Clone the repo to your machine
- Run " docker-compose up -d " from inside root directory of the project


Your app should be running on: http://localhost:3000
