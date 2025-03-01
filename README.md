# starterapp

1) Create the root app folder
2) Initialize a Git repository
3) Create a 'client' and 'server' subfolders
4) Cd into 'server' folder and create a .gitignore file containing the following:
```Git
.env
request.rest

# dependencies
/node_modules
/client/node_modules
/.pnp
/client/.pnp
.pnp.js
/client/.pnp.js

# testing
/coverage
/client/coverage

# production
# /build
# /client/build

# misc
.DS_Store
/client/.DS_Store
.env.local
/client/.env.local
.env.development.local
/client/.env.development.local
.env.test.local
/client/.env.test.local
.env.production.local
/client/.env.production.local

npm-debug.log*
/client/npm-debug.log*
yarn-debug.log*
/client/yarn-debug.log*
yarn-error.log*
/client/yarn-error.log*
# Elastic Beanstalk Files
.elasticbeanstalk/*
!.elasticbeanstalk/*.cfg.yml
!.elasticbeanstalk/*.global.yml
```
5) Run the following commands in terminal
```
npm init -y
npm i body-parser
npm i cors
npm i dotenv
npm i express
npm i http
npm i --save-dev nodemon
```
6) Add the following line to the scripts dictionary in the package.json file:
```
"dev": "nodemon server.js"
```
7) Open a new terminal window and cd into 'client' folder
8) Check the current node js version being used
```
nvm list
```
9) Select the desired node js version
```
nvm use v22.13.1
```
11) Run the following command:
```
npx create-react-app .
```
