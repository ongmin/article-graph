ArticleGraph
============

A demo implementation of a GraphQL endpoint for all of Article type data. Used as part of a tech talk on GraphQL.

## Getting Started

This repo is comprised of an api server and a graphiql front-end. The api runs on port 8091, graphiql on port 8092.

1. clone to local
2. npm install
3. npm start
4. [optional] npm run start-graphiql
5. run some queries
  - if running graphiql, then `open http://localhost:8092`
  - if not running graphiql, then just point curl or some other HTTP helper client at `http://localhost:8091/`
