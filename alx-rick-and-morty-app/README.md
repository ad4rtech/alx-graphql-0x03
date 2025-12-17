# Rick and Morty GraphQL App

This project is a Next.js application set up with:
- TypeScript
- ESLint
- Tailwind CSS
- Apollo Client (GraphQL)

It connects to the Rick and Morty GraphQL API using ApolloClient and enables running GraphQL queries inside React components.

## Setup Instructions

1. Install dependencies:

npm install @apollo/client graphql
npm install @types/graphql

2. GraphQL configuration is located in:
- graphql/apolloClient.ts
- graphql/queries.ts

3. Global ApolloProvider is configured in pages/_app.tsx.

Run the app:

npm run dev
