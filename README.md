# Hello World is an Flask API implemented using GraphQL

The application has implemented using **Ariadne**. Ariadne uses a schema-first approach.
Other libraries use to implement GraphQL in pyhon like **Graphene** and **Strawberry** use code first approach.

The main difference is that schema-first indicates that we first define the schema for the GraphQL service and then we implement the code by matching the definitions in the schema. In the code-first approach, we start by coding the resolvers, and then, from code as a single source of truth, we have the schema generated as an artifact.
