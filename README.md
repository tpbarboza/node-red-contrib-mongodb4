# node-red-contrib-mongodb2
MongoDB 3 driver node for Node-RED

Inspired from [node-red-bluemix-nodes](https://github.com/node-red/node-red-bluemix-nodes/tree/master/mongo) and [MongoDB 3 Driver](http://mongodb.github.io/node-mongodb-native/3.0)

Please refer to the [Collection documentation](http://mongodb.github.io/node-mongodb-native/3.0/api/Collection.html) to read about each operation.
To pass multiple parameters to an operation fill `msg.payload` with an array (do not include the last callback parameter).

# Change Log

## Original creation 0.1
Forked from MongoDB 2 driver node for Node-RED.
MongoDB 3 driver is originally based on MongoDB 2 driver node for Node-RED (https://github.com/ozomer/node-red-contrib-mongodb2)