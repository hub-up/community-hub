![CF](http://i.imgur.com/7v5ASc8.png) Midterm Project
=================================================

## Hubbub

### Author: Joseph Wolfe, Spencer Hirata, Aaron Bruce, and Alexander White

### Links and Resources
* [Orginization](https://github.com/hub-up)
* [Travis](http://xyz.com)
* [Back-end](https://github.com/hub-up/hub-back-end)
* [Front-end](https://github.com/hub-up/hub-front-end)

#### Documentation
<!-- * [Swagger](http://xyz.com) (API assignments only) -->
* [Jsdoc](http://xyz.com)

### Hub-back-end
#### `server.js`
##### Exported Values and Methods

###### `io.on('connection', socket => connect socket`

###### `socket.on('chat', payload => broadcast payload`

###### `socket.on('details', user => details for user`

###### `socket.on('disconnect', () => kill socket`

###### `socket.on('disconnect-start', payload => user disconnects`

###### `socket.on('emote', payload => user emote`

###### `socket.on('login', payload => user logs in`

###### `socket.on('nick', payload => user updates nickname`

###### `socket.on('private', payload => user send private message`

###### `foo(thing) -> string`

### Hub-Front-end
#### `user.js`
##### Exported Values and Methods

###### `Class User`
* Username
* Socket Id

#### `instructions.js`
##### Exported Values and Methods

###### `const instructions`
* /bye ← Disconnect from the server and exit the program
* /details ← See your name, the room you're in, and a list of other users in your current room
* /help ← This menu
* /leave  ← Leave the current room and return to the lobby
* /join ← Join an ongoing chat room
* /msg ← Send a direct message to another user
* /nick ← Update your username to a new name
* /room ←Create and automatically join a room

#### `client.js`
##### Exported Values and Methods

###### `rl.question(chalk.white(`${welcome}\n\nPlease enter a username: `), entry => sign in with username`

###### `rl.on('line', line => handle user input`

###### `rl.on('close', () => close program`

###### `function chatCommand(cmd, arg) { => handles instruction.js commands`

###### `bar(array) -> array`

### Setup
<!-- npm i -g (our app) -->
* git clone `hub-front-end`
* `npm i`

#### Running the app
* `npm start`
  
#### Tests
* How do you run tests? `npm test`
* What assertions were made?
* What assertions need to be / should be made?

### Diagrams



![UML Diagram 1](https://imgur.com/yQflV5m)