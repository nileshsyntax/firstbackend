## The working flow of Development
-> create folder and npm init
-> add readme file
-> git init -> set new branch name
-> set remote origin (github)
-> pushed initial commit
-> add bseci directoy and file
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