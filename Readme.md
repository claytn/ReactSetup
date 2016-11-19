# React Setup


## Running the code

After cloning, install third-party modules:

```sh
npm install
```

Then in one command-line window, to have Webpack build the bundle file (Make sure Webpack is installed first), do this:
```sh
webpack
```
or if you want Webpack to listen for any changes...
```sh
webpack -w
```

To pull up page on a server...

```sh
npm install webpack-dev-server
```
and then to start the server run ( from project root directory )
```sh
node_modules/.bin/webpack-dev-server
```
