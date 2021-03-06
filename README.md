Fringe is a framework agnostic **edge-runtime for serverless functions and graphql**.

It's inspired by frameworks like [Next.js](https://nextjs.org/) and [flareact](https://flareact.com/)

It supports following:

- File Based routing
- Dynamic API routes
- Serverless functions running at edge
- Serverless GraphQL - GraphQL queries running at edge

**Serveless GraphQL**

This is a POC to run GraphQL at edge along with caching responses in a normalized form at edge. Just declare your GraphQL queries in .graphql files during your development.

Project Structure:

![Image of Project Structure](https://user-images.githubusercontent.com/4037621/104008201-21147100-51cf-11eb-825b-5524b4457aa7.png)

The about.graphql can be run at REST endpoint http://localhost:8080/about/graphql/about

***Advantages***
- Removes all GraphQL client boilerplate from frontend builds.
- The model offers protection of origin GraphQL Server behind edge.
- Improves developer experience with more focus on business at hand than on setup.
- Write your component and define your GraphQL and keep them side by side with zero additional setup.
- Even execute GraphQL queries/mutations via file based routing for GraphQL.🔥

(In-progress :🌘 👇)

- Normalized Caching at edge of GraphQL results can offer better performance and again reduce the boilerplate for server codes.

**[Example Project](./test/fixtures)**

**Getting Started**

  ```
    cd into the root of project
    yarn build
    yarn run start 

    Now hit the link http://localhost:8080/about/graphql/man
  ```




