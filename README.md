# Auth GraphQL

**Handling authentication** with **GraphQL** is tricky and can be hard to implement if you are not familiar with the auth-flow when working with Apollo Client. This is a simple app which covers all the concepts of handling authentication in React apps using Apollo Client and GraphQL.

The project makes use of:
1. Express-GraphQL
2. MongoDB as Database.
3. Passport

## The project includes:
1. GraphQL API consumption using Apollo Client.
2. Managing authentication in GraphQL. Concept of protected and unprotected routes depending on whether user is logged in or not.

## How to run?
You can run this app on your local development machine by following the steps provided below:

1. Clone the repo or download zip file.
2. Go to server directory.
3. Please insert your MongoDB URI in server.js file. The URI can be accessed from MongDB atlas.
4. Install dependencies by running the script `npm install`.
5. Run the server by running the script `npm start`. The server will run on localhost:4000.
6. You can access the graphiql playground on http://localhost:4000/graphql.
7. Go to previous directory and run script `npm install`.
8. Run the app by running the script `npm start`. The app will run on http://localhost:3000.

