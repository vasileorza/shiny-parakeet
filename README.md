# Yet Another Angular Seed

This project is meant to be used for training purposes. It provides a basic HTTP sevrer configuration and REST API over a set of JSON stored items.

### Instalation

The source code can be either cloned via GIT as shown below, or simply copied as a zip archive locally.
```
git clone https://github.com/vasileorza/shiny-parakeet.git
```
After downloading the project sources, install the NPM dependencies by running the command shown below in the project root folder. This will download locally the `live-server` and `json-server` NPM modules.
```
$ npm install
```

### Usage Instructions
The server can be started by running the `npm start` command in the project root folder. The port `8080` will be used for serving the contents of the `index.html` file, while the `3000` port will expose the Heroes `REST API`.

```
$ npm start

    > Home Page
    > http://127.0.0.1:8080
    > Resources
    > http://localhost:3000/heroes
```
And that's it...
