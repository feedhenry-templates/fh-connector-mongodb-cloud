FORMAT: 1A

# FeedHenry MongoDB Connector
[![Dependency Status](https://img.shields.io/david/feedhenry-templates/fh-connector-mongodb-cloud.svg?style=flat-square)](https://david-dm.org/feedhenry-templates/fh-connector-mongodb-cloud)

The FeedHenry MongoDB Connector. For more information on MongoDB see: [https://github.com/mongodb/node-mongodb-native](https://github.com/mongodb/node-mongodb-native).

# Group MongoDB Connector API

# MongoDB [/cloud/mongodb]

Insert into MongoDB

## MongoDB [POST] 

Insert a document into a MongoDB Collection

+ Request (application/json)
    + Body
            {
              "collection": "my_collection",
              "insert": {"foo": "bar"}
            }

+ Response 200 (application/json)
    + Body
            {
              "ok": "true"
            }
