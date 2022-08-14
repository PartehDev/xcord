# XCord
A direct Minicord clone
```bash
# clone the repo
$ git clone https://github.com/PartehDev/xcord.git

$ cd xcord

# install the node modules...
$ npm install

# start
$ npm start
```
Make sure you start mongodb or correct env var...
```js
config.dbURL = process.env.DATABASEURL || "mongodb://localhost/xcord";
```


## Built with

* [Socket io](https://github.com/socketio/socket.io) - Realtime application framework
* [Nodejs](https://github.com/nodejs/node) - Node.js JavaScript runtime

## Upcomming Features
- [ ] Friends Request, sending/add people to friends list...
- [ ] Real time one to one chat with friends...
- [ ] Direct message friends...
- [ ] Received Message Notifications...
- [ ] Emoji Sharing...
- [ ] Image Sharing within chat...
- [ ] Files Upload and sharing...
