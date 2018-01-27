# MicroPosts

A JavaScript application with REST API.

![microposts](https://github.com/vgorbic1/microPosts/blob/master/microposts.jpg)

## Usage

### Installation

Install the dependencies

```sh
$ npm install
```

### Serve
To serve in the browser  - Runs webpack-dev-server

```sh
$ npm start
```

### Serve JSON
To imitate REST API use [json-server](https://github.com/typicode/json-server).
Install and run it.

```
$ json-server --watch db.json
```
Configure correct url to json-server endpoints in app.js

### Build
Compile and build

```sh
$ npm run build
```