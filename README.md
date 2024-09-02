# Chat-Box
Live Demo
Features
Join a specified room to chat

Send the geographical location to other users in the room if permission is granted

Automatically scroll down upon receiving a new message

Responsive web design (RWD)

Getting Started
Follow the instructions below to set up the environment and run this project on your local machine

Prerequisites
Node.js
Installing
Download ZIP or clone this repo
> git clone https://github.com/Mehulcoder/Chat-Application.git
Install dependencies via NPM
> npm install
Back to the root directory and type the below command to start the server and the service
> npm run dev
See it up and running on http://localhost:8000
Deployment
Deploy to Heroku
> heroku create
> git push heroku master
Open the app in the browser
> heroku open
Built With
Frontend
jquery
mustache
Backend
express
NodeJS
compression
helmet
Utils
socket.io
moment
Notes
Send an event to everybody in the room 'The Office Fans'
io.emit -> io.to('The Office Fans').emit

Send an event to everybody in the room 'The Office Fans' except for the current user
socket.broadcast.emit -> socket.broadcast.to('The Office Fans').emit

Send an event to a specific user
socket.emit
Authors
Akash Kolukonda
