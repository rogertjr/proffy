<h1 align="center"> Proffy </h1>

## Project

React Native + ReactJS + NodeJS project developed on RocketSeat NexLevelWeek. This project is based on an application for connect students and teachers.

## Technologies

This project was developed with the following technologies:

- API:

  - [NodeJS](https://nodejs.org/en/)
  - [Typescript](https://www.typescriptlang.org/)
  - [ts-node-dev](https://github.com/whitecolor/ts-node-dev)
  - [Express](https://expressjs.com/)
  - [KnexJS](http://knexjs.org/)
  - [PostgreSQL](https://www.npmjs.com/package/sqlite3)
  - [Cors](https://www.npmjs.com/package/cors)
  - [bcrypt](https://www.npmjs.com/package/bcrypt)
  - [JsonWebToken](https://www.npmjs.com/package/jsonwebtoken)

- Web:

  - [ReactJS](https://reactjs.org/)
  - [Typescript](https://www.typescriptlang.org/)
  - [React Router v5](https://github.com/ReactTraining/react-router)
  - [Axios](https://github.com/axios/axios)
  - [styled-components](https://styled-components.com/)
  - [Yup](https://www.npmjs.com/package/yup)
  - [Unform](https://unform.dev/)

- Mobile:

  - [React Native](https://reactnative.dev/)
  - [Expo](https://expo.io/)
  - [Typescript](https://www.typescriptlang.org/)
  - [React Navigation v5](https://reactnavigation.org/)
  - [styled-components](https://styled-components.com/)
  - [Axios](https://github.com/axios/axios)

## Configuration

Before run this application, you'll need installed on your computer:
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/)
- [Yarn v1](https://classic.yarnpkg.com/) 
- [Expo](https://expo.io/) to run the Mobile app.
- [Docker](https://www.docker.com) to run an instance of [PostgreSQL](https://www.postgresql.org/).

Server:

```bash
# Create the instance of postgreSQL using docker
$ docker run --name proffyPG -e POSTGRES_USER=docker \
              -e POSTGRES_DB=proffy -e POSTGRES_PASSWORD=docker \
              -p 5432:5432 -d postgres

# Go into the backend folder
$ cd backend
```

Make a copy of .env.example to .env and set YOUR enviroment variables

```bash
# Install all the dependencies
$ yarn

# Run the app
$ yarn dev
```

Frontend:

```bash
# Go into the web folder
$ cd web

# Install all the dependencies
$ yarn

# Run the app
$ yarn start
```

Now you can access in your browser: http://localhost:3000


Mobile:

```bash
# Go into the mobile folder
$ cd mobile

# Install all the dependencies
$ yarn

# Run the app
$ yarn start
```

Your browser should open and you just need to scan the QR Code to your phone.