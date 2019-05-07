[Back to Course Overview](https://sem4-fullstack-javascript.github.io/Fullstack-JavaScript/)

# Hand-in-Period-4

## Explain shortly about GraphQL, its purpose and some of its use cases

## Explain some of the Server Architectures that can be implemented with a GraphQL backend

### GraphQL server with a connected database
<img src="https://imgur.com/cRE6oeb.png" width=50%>

### GraphQL layer that integrates existing systems
<img src="https://imgur.com/zQggcSX.png" width=50%>

### Hybrid approach with connected database and integration of existing system  
<img src="https://imgur.com/73dByTz.png" width=50%>

## What is meant by the terms over- and under-fetching in relation to REST

Over-fetching is fetching too much data. There is data in the reponse you don't use.  
Under-fetching is not having enough data with one call to an endpoint, leading you to call a second endpoint.

In both cases, they are performances issues : you either use more bandwidth than you should, or you are making more HTTP requests that you should.

GraphQL fixes this problem because it allows access to an arbitrary set of data exposed by the server. You specifically specify what you need and will get this data, and only this data, in one trip to the server.

## Explain shortly about GraphQL’s type system and some of the benefits we get from this

## Explain shortly about GraphQL Schema Definition Language, and provide a number of examples of schemas you have defined

## Provide a number of examples demonstrating data fetching with GraphQL. You should provide examples both running in a Sandbox/playground and examples executed in an Apollo Client

## Provide a number of examples demonstrating creating, updating and deleting with Mutations. You should provide examples both running in a Sandbox/playground and examples executed in an Apollo Client

## Explain the Concept of a Resolver function, and provide a number of simple examples of resolvers you have implemented in a GraphQL Server

## Explain the benefits we get from using a library like Apollo-client, compared to using the plain fetch-API

## In an Apollo-based React Component, demonstrate how to perform GraphQL Queries, including:

### Explain the structure of the Query Component

### Explain the purpose of ApolloClient and the ApolloProvider component

### Explain the purpose of the gql-function (imported from graphql-tag)

## In an Apollo-based React Component, demonstrate how to perform GraphQL Mutations

## Demonstrate and highlight important parts of a “complete” GraphQL-app using Express and MongoDB on the server side, and Apollo-Client on the client
