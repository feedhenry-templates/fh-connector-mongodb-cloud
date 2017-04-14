# FeedHenry MongoDB Connector

[![Dependency Status](https://img.shields.io/david/feedhenry-templates/fh-connector-mongodb-cloud.svg?style=flat-square)](https://david-dm.org/feedhenry-templates/fh-connector-mongodb-cloud)

The FeedHenry MongoDB Connector. For more information on MongoDB see: [https://github.com/mongodb/node-mongodb-native](https://github.com/mongodb/node-mongodb-native).

## Group MongoDB Connector API

### Insert into MongoDB

Insert a document into a MongoDB Collection

|              |                | 
|--------------|----------------|
| Endpoint     | /cloud/mongodb |
| HTTP Method  | POST           |

#### Request (application/json)

##### Body

```json
{
  "collection": "my_collection",
  "insert": {"foo": "bar"}
}
```

#### Response 200 (application/json)

##### Body

```json
{
  "ok": "true"
}
```

## Tests

All the tests are in the "test/" directory. The cloud app is using mocha as the test runner. 

### Unit tests

```shell
npm run unit
```

or

```shell
npm run test
```

### Unit coverage

```shell
npm run coverage
```
