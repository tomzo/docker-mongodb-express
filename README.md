# MongoDB-express in docker

There is also an *official* [docker image](https://github.com/mongo-express/mongo-express#usage-docker) `mongo-express`.
This build is a little different:

 * uses [node-alpine](https://github.com/inadarei/node-alpine) base image
 * node application runs under runit so that it restarts in case it crashes
