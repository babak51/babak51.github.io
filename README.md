# babak51.github.io
This is an exercise is using webpack to bundle a React sample application.
All that the server needs are the index.html withwhich has a div element with id="root", and a bundle.js file.

To create the bundle.js the following command is given from the project folder:
>npm run build

The package.json is as follow:
{
  "name": "recipes-app",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack --mode development"
  },
  "keywords": [],
  "author": "Me",
  "license": "ISC",
  "dependencies": {
    "react": "^16.13.1",
    "react-dom": "^16.13.1",
    "serve": "^11.3.2"
  },
  "devDependencies": {
    "@babel/core": "^7.11.4",
    "@babel/preset-env": "^7.11.0",
    "@babel/preset-react": "^7.10.4",
    "babel-loader": "^8.1.0",
    "webpack": "^4.44.1",
    "webpack-cli": "^3.3.12"
  }
}
