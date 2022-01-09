#  Build a full stack message board with Node/Express/MongoDB/Vue.js/Bootstrap

See [Build a full stack message board with Node/Express/MongoDB/Vue.js/Bootstrap](https://youtu.be/2xIoWm08SBM) YouTube video
by Coding Garden


## Mongo

Follow these steps to install MongoDB Community Edition using Homebrew's brew package manager. Be sure that you have followed the installation prerequisites above before proceeding.

1. Tap the MongoDB Homebrew Tap to download the official Homebrew formula for MongoDB and the Database Tools, by running the following command in your macOS Terminal:

               brew tap mongodb/brew

If you have already done this for a previous installation of MongoDB, you can skip this step.

2. To install MongoDB, run the following command in your macOS Terminal application:

               brew install mongodb-community@5.0

he installation includes the following binaries:

1. The mongod server
2. The mongos sharded cluster query router
3. The MongoDB Shell, mongosh

## now

* [Publicar una app Node en Zeit Now en unos sencillos pasos](https://mugan86.medium.com/publicar-una-app-node-en-zeit-now-en-unos-sencillos-9386dc2f966d)

## How to deploy a SPA JAM Stack app?

To start mongodb/brew/mongodb-community now and restart at login:

  brew services start mongodb/brew/mongodb-community

Or, if you don't want/need a background service you can just run:


  mongod --config /usr/local/etc/mongod.conf