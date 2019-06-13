[<img src="https://github.com/szympol/26._ChatApp/blob/master/images/main.JPG?raw=true" align="right" alt="Authenticate applications using Google" width="40%">](https://github.com/szympol/26._ChatApp/)

# ChatApp

**`[React, ExpressJS, Socket.io, Webpack]`**

It is a simple Chat application. Join the room and start sharing your thoughts.

This app is based on user stories with Acceptance Criteria:

- **1st user story**:
  *As a chat user
  In order to join the chat
  I want to select my user name and join the chat*
  - if the user isn't signed in, the app should show a simple view with one input for the user's nickname,
  - there should be a simple validation for that input (if the name is empty, don't leave the page),
  - writing down the nickname and pressing enter should redirect the user to chat view,
  - signing in to the chat should communicate other users that a new person has joined,
- **2nd user story**:
  *As a chat user
  In order to know who is online
  I want to see a list of users and the number of people who are online*
  - on the chat view, the user should see the number of people available online,
  - the aforementioned number should be dynamic so that when another user joins or leaves, the number changes,
- **3rd user story**:
  *As a chat user
  In order to talk to other users
  I want to send messages to chanel and see what another user wrote instantly, without refreshing the page*
  - There should be an input where new messages can be written,
  - When the enter key is pressed, the message should be sent,
  - After sending a message, the input should be cleared,
  - The message that was sent should be displayed on the messages list,
  - Other users should see the message that was sent as well,
- **4th user story**:
  *As a chat user
  In order to know if other person wrote something on chat
  I want to see some kind of notification*
  - a message sound should be played,
  - a dot of unread message should appear.

## Getting Started

<!-- - [View project online](https://szympol.github.io/26._ChatApp) -->
This project requires a server to start working.

Please follow instructions below, if you are willing to run the project locally.

### Prerequisites

Both [Git](https://git-scm.com/downloads) and [Node](https://nodejs.org/en/download/) are required to run this project locally.

### Installing

Please copy and paste below commands to your Git terminal step by step to get a development env running.

Download a repository:

```node
git clone git@github.com:szympol/26._ChatApp.git chatApp
```

Go to the project working directory:

```node
cd chatApp
```

Install all of the dependencies with the following command:

```node
npm install
```

View the project

```node
npm run watch
```

then

```node
Open `localhost:3000` at least twice in the seperate browser windows. Now you can communicate between two users on the server.
```

#### Under the hood of `npm commands`

- `npm run watch` - this command starts a server at `localhost:3000`. It also monitors for any changes in `index.js` file and automatically restart the server. This command is responsible for backend
- `npm run start` - it build a development app,
- `npm run build` - it builds a production app.

`npm run start` && `npm run build` commands compile the logic written in React into modules according ES6 standards. The compiled JS file is injected into a body of a template html file.
If you are not sure how these commands work, please visit this site [Webpack](https://webpack.js.org/guides/production/).

## Built With

- [Express](https://expressjs.com/) - fast, unopinionated, minimalist web framework for Node.js,
- [React](https://reactjs.org/) - a JavaScript library for building user interfaces,
- [Socket.io](https://socket.io/) - the fastest and most reliable real-time engine,
- [Webpack](https://webpack.js.org/) -  static module bundler for modern JavaScript applications.

## Author

- **Szymon Polanowski** - [GitHub Account](https://github.com/szympol)

## License

This project is licensed under the MIT License.
