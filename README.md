### required commands to create ReactApp and integrate it with AWS Amplify 

npm install -g @aws-amplify/cli - This will install aws-amplify
npx create-react-app graphql-microservice - This will create react app
amplify init - To integrate your app with AWS Amplify. Cloudformation will do require setup/installations for GraphQL and React application and create amplify-graphqlmicroservice-dev environment of Amplify
"amplify add api" to create a backend API
"amplify push" will build all your local backend resources and provision it in the cloud


### other command for information
"amplify status" will show you what you've added already and if it's locally configured or deployed
"amplify add <category>" will allow you to add features like user login or a backend API
"amplify console" to open the Amplify Console and view your project status
"amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud