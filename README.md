# a-chat: Anonymous Chat

> All work and no play makes Jack a dull boy
> -the shining ( 1980 )

a-chat: A real-time chat application, based on WebSockets, used for meeting up with some random strangers and keeping your identity anonymous.
## Description
So this chat application which serves from 00:00 to 01:00 only *:P* , creates an interface of chat between pairs of anonymous users among all the users online.
###### Features
- Real-time interaction with WebSockets
- Video and Audio calls using WebRTC
###### Things to learn
- How to create a basic node chat application, for say 200 users.
- Solving complexities like reconnection after server restart.
- Scaling the server with a cluster of node applications, using docker, and still maintaining an internode connection between all sockets/users.
- Large scaling for a million users and load testing.
___
##### Proposed Tech. Stack
- MERN `MongoDB, ExpressJS, NodeJS, ReactJS`
- [socket.io](https://socket.io/)
- [docker](https://www.docker.com/)

## Steps to setup locally and run:

* ### Install [Node.js](https://nodejs.org/en/download/current/)
> Deploying this app requires node package manager `npm` and the development server requires [nodemon](http://nodemon.io) to be installed using:
>  ```
>  npm i -g nodemon
>  ```

* ### Clone the repository
> Download this repository `or`
```
git clone https://github.com/pclubiitj/a-chat.git
cd a-chat
```
* ### Install dependencies
```
npm install
```
* ### Run `server`
```
npm start
```
> The server will start listening by default at http://localhost:3000
* ### Run `development server` using nodemon
```
npm run dev
```


## Team

|Name|Year|Department|
|--|--|--|
|[Kunal Tawatia](https://github.com/kunaltawatia)| Sophomore|Computer Science and Engineering|
|[Rohan Singh](https://github.com/rohansingh9001)| Freshman| Electrical Engineering|
|[Tarun Tomar](https://github.com/TarunTomar122)|Freshman|Computer Science and Engineering|
|[Pratyaksh Tyagi](https://github.com/pratyaksh123)| Freshman| Electrical Engineering|
|[Harish Kumar](https://github.com/harishk1619)| Freshman | Computer Science and Engineering|
|[Harshil Bhatia](https://github.com/HarshilBhatia)| Freshman| Computer Science and Engineering|
|[Shubham Agrawal](https://github.com/agrawalshubham01)|Freshman|Bio Engineering|
|[Abhishek Raghav](https://github.com/imraghav20)| Freshman|Computer Science and Engineering|
|[Saptashrungi](https://github.com/Saptashrungi)|Freshman|Computer Science and Engineering|
|[Bhawna Chopra](https://github.com/bhawnachopra2002)| Freshman|Electrical Engineering|
|[Anshul Goyal](https://github.com/Anshulpg)|Freshman|Computer Science and Engineering|
|[Akshika Gupta](https://github.com/guptaakshika09)|Freshman|Computer Science And Engineering|

##### Steps to join

 1. Star this repo.
 2. Push a PR in this README, adding your details in the above table.
