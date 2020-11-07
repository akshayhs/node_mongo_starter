# Node.js applications with MongoDB on the backend

A simple repository for quickly getting started with Node.js applications running a MongoDB database on the backend.

## Packages already installed

| **Package** | **Use-case** |
| --- | --- |
| body-parser | Parsing incoming requests in the middleware |
| connect-mongodb-session | session storage on the server side |
| dotenv | For storing environment variables |
| ejs | templating |
| express | The framework used for the Node.js application |
| express-session | session management for the application |
| method-override | Overriding request verbs |
| mongoose | The ODM[^1] for MongoDB |
| moment-timezone | For timezone related information |

## Getting started

**1. Make sure the repository is cloned to your local machine**.

**2. Install the packages from the `package.json` file**.

```bash
npm i
```

**3. Run the following command**

```bash
# npm run dev for developers
npm run start
```

[^1]: [Object Data Modelling](https://devcenter.heroku.com/articles/nodejs-mongoose)