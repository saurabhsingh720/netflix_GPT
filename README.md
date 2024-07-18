# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

# features

- login/sign up
  - sign in/ sign up form
  - redirect to browse page
- browse(after athentication)
  - header
  - main menu
    - tailer in background
    - title & description
    - movie suggestions
      - movie lists\*n
- netflixGPT
- search bar
- movie suggestion

# shortcut for emmet

- rafce

# NetflixGPT

- create react app
- configured tailwind css
- header
- routing of app
- login form
- sign up form
- form validation
  - useRef hook
- firebase setup
- deploying our app to production
- create signup user account in firebase
- register app
- npm install firebase
- npm install -g firebase-tools
- if firebase login is not working then use      Set-ExecutionPolicy RemoteSigned -Scope CurrentUser in windows powershell
- firebase login
- firebase init
- firebase deploy

- added sign up and sign in code from firebase using api
- done authentication of users using email and password
- adding the data in redux store
- installing redux using   npm install -D @reduxjs/toolkit
- then install
  npm install react-redux
- created appStore
- created userSlice
- learned onAuthStateChanged
- learned about dispatch, navigate hooks
- BugFix: sign up user displayName and profile picture update
- BugFix: if the user is not logged in redirect/ browse to login page and vice-versa
- unsubscribed to the onAuthStateChanged callback
- implemented sign out
- done update profile
- fetch movies from tmdb
- register TMDB API and create an app and get acces token from api section
- get data from TMDB now  playing movies list api
- custom hook for now playing movies
- create movieSlice
- updated store with movies data
- planning for main container and secondary container
- fetch data from trailer video
- update store with trailer video data
- embedded the youtube video and make it autoplay and muted
- added tailwind css to make the main container look awesome
- build our secondary components
   - //secondary component planning

     - movielist -popular
      - movieCard*n
     - movielist - now playing
     - movielist - trending
     - movielist - tvshow
- build movie list
- build movie card
- tmdb image cdn url finded
- made the browse page amazing with tailwind css 
- created custom hooks for usePopularMovies, useUpcomingMovies, useTrendingMovies,
useTvMovies
- adding GPT search feature
  - added GPT Search page
  - added GPT Search bar
- added multilanguage feature in our app
- integrating GPT api
- get open ai api key
- GPT search api call
- fetched gptmovies suggestions from tmdb
- created gptSlice added data
- reUsed movieList component to make movie suggestions container
- memoization
- added .env file
- adding .env file to gitignore
