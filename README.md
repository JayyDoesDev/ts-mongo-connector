# ts-mongo-connector
 ts-mongo-connector allows you to connect to your mongodb easy and fast in typescript.

 ## Setup For TypeScript

 ```typescript
 import mongoConnect from 'ts-mongo-connector'

 const client: mongoConnect = new mongoConnect()

 client.c("database url")
```

## Setup For JavaScript

```javascript
const { MongoConnect } = require("ts-mongo-connector");

const client = new MongoConnect()
client.c("database url")
```