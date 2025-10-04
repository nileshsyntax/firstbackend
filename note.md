## The initial working flow of setup Development project
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
-> adding Prettier setting in project
    -> create .prettierrc file - a prettier configaration file
    -> configuring standard prettier format


# Proper professional production grade project structure setup
### /src directory structure

`/controllers`  - majorly functionlity 
`/db`           - database connection logic
`/middlewares`  - 
`/models`       - 
`/routes`       -
`utils`         - 
