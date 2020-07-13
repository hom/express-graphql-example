# express-graphql-example

An example project of express-graphql

## Start

1. Install node modules
```js
yarn install
```

2. Run graphql server
```js
node index.js
```

3. Fetch graphql example data
```bash
curl -X POST \
     -H "Content-Type: application/json" \
     -d '{"query": "{ hello }"}' \
http://localhost:4000/graphql

# output:
{"data":{"hello":"Hello World"}}
```