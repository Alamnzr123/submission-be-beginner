# submission-be-beginner

## Installation

1. Clone the repo `git clone https://github.com/Alamnzr123/submission-be-beginner.git`
2. Run `npm install` to install the dependencies
3. Run with :
   - `npm run start` : if you want to run it in client mode (use `node`) without auto restart on every changing code
4. You are Ready to Go

## Table of contents

- [Features](#Features)
- [Commands](#Commands)
- [Project Structure](#Project-Structure)
- [API Documentation](#API-Documentation)
- [Packages Included](#Packages-Included)
- [Tools and Technologies](#Tools-and-Technologies)

## Features

- **API documentation:** with [Postman](https://www.postman.com/)
- **Dependency management:** with [NPM](https://www.npmjs.com/)
- **Security:** set security HTTP headers using [helmet](https://helmetjs.github.io/)
- **Linting:** with [ESlint](https://eslint.org/)
- **CRUD:** [Hapi](https://www.npmjs.com/package/@hapi/hapi)

## Commands

Running in client mode:

```
npm run start
```

## Project Structure

```
|── Backend
   |── node_modules    # module files
   |── src             # Project source code
       |── books.js    # empty
       |── handler.js  # Controller
       |── routes.js   # Routes
       |── server.js   # index file
   |── .eslintrc.json  # ESlint
   |── .gitignore      # File name for not uploaded on github
   ├── Bookshelf API Test.postman        # API Documentation
   |── package.json    # modules files
```

## API Documentation

### API Endpoints - Backend

List of available routes:

**GET BOOKS**\
`GET /books`

**ADD BOOKS**\
`GET /books`

**GET BOOKS BY ID**\
`GET /books/{bookId}`

**UPDATE BOOKS BY ID**\
`PUT /books/{bookId}`

**DELETE BOOKS BY ID**\
`DELETE /books/{bookId}`

**NOT FOUND**\
`* /{any*}`

### Frontend Repository

`https://github.com/Alamnzr123/submission-fe-beginner`

## Tools and Technologies
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Hapi](https://img.shields.io/badge/hapi-%2523404d59.svg?style=for-the-badge&logo=hapi&logoColor=%252361DAFB)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)


## Packages Included

- NPM dependencies

  ![](https://img.shields.io/badge/@hapi/hapi-v20.1.2-blue)
  ![](https://img.shields.io/badge/moment-v2.29.1-blue)
  ![](https://img.shields.io/badge/nanoid-v3.1.22-blue)
  ![](https://img.shields.io/badge/nodemon-v2.0.7-blue)
