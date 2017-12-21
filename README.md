# node-todo-api

Created during the Udemy course [The Complete Node.js Developer Course (2nd Edition)](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/overview)

## Setup

```
git clone [this repo url]
cd [repo name]
npm install
cp server/config/example.config.json server/config/config.json
```
Remember to fill in the blanks in config.json.

## Install MongoDB on macOS

```
brew install mongodb
mkdir -p /data/db
sudo chmod 755 /data/db
mongod
```

## Running the app

```
node server/server.js || npm start
nodemon server/server.js

npm test
npm run test-watch
```
