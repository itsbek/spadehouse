# Installation

1. `npm install` or `yarn` to install the dependencies
2. Create your own environment variables as demonstrated in `.env.example` file
3. `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET` variables taken from github app(create an app on github) to sign in with github

# Launch

 Run `npm run migrate` to seed the database

1. `npm run server` - Starts the Express server
2. `npm run dev` - starts NextJS app

# Tech-stack

## Frontend:
- NextJS / ReactJS
- Redux Toolkit
- simple-peer (WebRTC)
- Socket.IO
- Axios

## Backend:
- NodeJS
- Express
- Sequelize
- Passport
- JWT
- Multer
