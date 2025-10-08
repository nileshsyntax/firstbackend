## The initial project setup flow
-> create folder and npm init
-> add readme file
-> git init -> set new branch name
-> set remote origin (github)
-> pushed initial commit
-> add basic directoy and file
	-> /public/temp
	-> .gitignore, .env
	-> /src/app.js constant.js index.js
-> package.json initial configuration
	-> set type: module for modulejs
    -> using nodemon (npm -i -D nodemon, dev dependencies)
    -> add nodemon to automate relode start script after saving
```json
     "scripts": {
    "dev": "nodemon src/index.js"
  },
```
-> adding Prettier setting in project
-> create .prettierrc confit file
-> configuring standard prettier format


# Proper professional production grade JS Backend project structure setup
-> node init directory
-> Git init, and gitigonre
-> configure .env
-> configure package.json
-> configure prettier
-> Directory Setup

### directory setup structure
**/public, public/temp**


**The `/src` directory structure**

`/controllers`  - majorly functionlity 
`/db`           - database connection logic
`/middlewares`  - 
`/models`       - 
`/routes`       -
`utils`         - 

 # How to connect database in MERN with debugging
 