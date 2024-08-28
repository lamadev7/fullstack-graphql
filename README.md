# Fullstack-Graphql

## GraphQL Key Points
 1. TypeDefs - Schema
 2. Resolvers - Business logic

## Setup
  1. Install basic packages
     
     ```
      npm i express apollo-server@latest apollo-server-core@latest
     ```

  2. Create entry file `server.js`
     ```
        // import server configuration packages
        import { ApolloServer, gql } from "apollo-server";
        import { ApolloServerPluginLandingPageGraphQLPlayground } from "apollo-server-core";

        
     ```
