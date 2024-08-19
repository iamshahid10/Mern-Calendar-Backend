# MERN Calendar

# Overview
*	Name: MERN Calendar

*	Description: A web application for managing events, including adding, editing, deleting, and listing events. Developed using the MERN stack with integrated authentication, JWT, Redux for state management, and a calendar interface.

*	Technology Stack: React, Redux, Node.js, Express.js, MongoDB

*	Version: 1.0.0

## [Try demo]()

### Table of contents 📃

- [MERN Calendar](#mern-calendar)
  - [Try demo](#try-demo)
    - [Table of contents 📃](#table-of-contents-)
  - [Starting 🚀](#starting-)
    - [Pre-requirements 📋](#pre-requirements-)
    - [Installation 🔧](#installation-)
  - [Deployment 📦](#deployment-)
  - [Built with 🛠️](#built-with-️)

## Starting 🚀
  
### Pre-requirements 📋

* [Git](https://git-scm.com/)
* [npm](https://www.npmjs.com/)
* [Mongo database](https://www.mongodb.com/)

### Installation 🔧

Local installation:

```bash
# Clone this repository
$ git clone [Repository URL]
```

---

**Backend setup:**
```bash
# Change directory to the Backend path
$ cd Backend

# Install dependencies
$ npm install
```

Backend **.env** file setup:

```shell
PORT=5000
MONGODB_CNN=mongodb+srv://user:password@clusterrestaurant.rgq1n.mongodb.net/schema
JWT_SECRET_KEY=RANDOMKEY
```

---

**Frontend setup:**
```bash
# Go back to the project path
$ cd ..

# Change directory to the Frontend path
$ cd Frontend

# Install dependencies
$ npm install
```

Frontend **.env** file setup:

```shell
REACT_APP_API_URL="http://localhost:5000/api"
```

## Deployment 📦

```bash
# Open terminal in project path and run
$ cd Backend
$ npm start


# Open another terminal in project path and run
$ cd Frontend
$ npm start
```
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Built with 🛠️

* [React](https://es.reactjs.org/) - Frontend framework
* [React Redux](https://react-redux.js.org/) - State management
* [Node.js](https://nodejs.org/) - Javascript runtime environment
* [Express.js](https://expressjs.com/) - Backend framework
* [MongoDB](https://www.mongodb.com/) - NoSQL database

---
⌨️ with ❤️ by [Mohammad Shahid](https://github.com/iamshahid10 ) 😊 