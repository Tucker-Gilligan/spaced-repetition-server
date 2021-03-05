# Spaced repetition API!
## Links
- Live Deployment: https://spaced-repetition-tucker.vercel.app/register
- Server Repository: https://github.com/Tucker-Gilligan/spaced-repetition-server
- Client Repository: https://github.com/Tucker-Gilligan/spaced-repetition-client

## Summary

This is a language learning application using the Spaced Repetition learning technique!

## Endpoints

### /api/user
### /api/auth

- POST requests authorization
- Used for logging in and 

<img src="https://user-images.githubusercontent.com/72029209/110063754-bd737380-7d39-11eb-9fd2-880f6e7e7472.png" alt="login page" width="200px">

<img src="https://user-images.githubusercontent.com/72029209/110064478-2ad3d400-7d3b-11eb-8e32-1c5f4c126af9.png" alt="registration page" width="200px">



### /api/language

- GET requests
- this endpoint returns a list of a user's languages, and the words being studied in that language

<img src="https://user-images.githubusercontent.com/72029209/110063756-be0c0a00-7d39-11eb-9f78-63addc5de556.png" alt="Dashboard" width="200px" />



### /api/language/head

- GET requests
- This endpoint will return the next word to be studied

<img src="https://user-images.githubusercontent.com/72029209/110063757-be0c0a00-7d39-11eb-9747-65ea4662ca7d.png" alt="Learning Route" width="200px" />


### /api/language/guess
- Users can POST their guess to each word as displayed in the /head endpoint, and receive feedback based on their response.
- User's guess determines the position where the word will be placed in the list
<img src="https://user-images.githubusercontent.com/72029209/110063761-be0c0a00-7d39-11eb-9fc4-0eeff67a6a4a.png" alt="Feedback Page" width="200px" />

## Technology Used

### Client:

- ReactJS
- react-router-dom for routing and in-app navigation
- CSS (vanilla CSS)
- Babel
- Webpack
- Vercel for deployment
- Cypress for testing

### Backend:

- Express for handling API requests
- NodeJS for interacting with the file system
- Postgrator for database migration
- Mocha, Chai, Supertest for endpoints testing
- Knex.js for interfacing with PostgreSQL database
- Heroku for database and server deployment
