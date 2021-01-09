# phaser3-tutorial
implementation of the [phaser3 tutorial](http://phaser.io/tutorials/making-your-first-phaser-3-game/part1)

## Setup
Clone and install dependencies. The phaser3 package is unecessary, there is a script to load it actually. We just need `http-server` to serve static assets

`npm install`

## http-server
The browser will block access to static assets. To get around this, one option is to serve the images ourselves, or use a chrome extension. This is the one that worked for me. I was able to set CORS permissions explicitly to allow all '*'

## Start game
run the server with `npm start` and navigate to the `index.html` from your filesystem in a browser


![](assets/gameplay.gif)
