# About this project

## ivMusic

**ivMusic** is a useless React app for creating new playlists with Spotify. 
- Deployed with surge at [ivMusic](https://ivmusic.surge.sh/).


## Codecademy
Project built during my [Full-Stack Engineer Career Path Course on Codecademy](https://www.codecademy.com/learn/paths/full-stack-engineer-career-path).

## Features

* Spotify Login — the first time a user searches for a song, album, or artist, Spotify will ask them to log in or set up a new account.
* Search by song, album, or artist — a user can type the name of a song, artist, or album into the search bar and click the SEARCH button.
* Populate results list — ivmusic displays the list of returned tracks from the user’s query.
* Add song to a Custom Playlist — users can add a track to their playlist by clicking a ‘+’ sign on the right side of the track’s display container.
* Remove song from Custom Playlist — users can remove a track from their playlist by clicking a ‘-’ sign on the right side of the track’s display container.
* Change playlist title — users can change the title of their custom playlist.
* Save playlist to account — users can save their custom playlist by clicking the  SAVE TO SPOTIFY button.

## Potential future improvements

* Pressing enter triggers a search
* Include preview samples for each track
* Only display songs not currently present in the playlist in the search results
* Add a loading screen while playlist is saving
* Update the access token logic to expire at exactly the right time, instead of setting expiration from when the user initiates their next search
* After user redirect on login, restoring the search term from before the redirect
* Ensure playlist information doesn’t get cleared if a user has to refresh their access token

## Codecademy Instructions

**Intro**

In this project, you will build a React web application. You will use your knowledge of React components, passing state, and requests with the Spotify API to build a website that allows users to search the Spotify library, create a custom playlist, then save it to their Spotify account.

In this course, we teach both class components and function components. We start with class components because they are still widely used in legacy code, are common in tutorials/documentation found online, and are required for a few specific use-cases. In the module on Hooks, we introduce function components which are the recommended way of creating React components. From that point on, we use function components throughout the remainder of our React content.

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
