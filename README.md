# movie-site-sample-frontend
This repository will reflect how to communicate with a backend service written in Spring Boot

## Source

- I am following this [youtube tutorial](https://www.youtube.com/watch?v=5PdEmeopJVQ&ab_channel=freeCodeCamp.org)
- Related `backend logic` is available [here](https://github.com/atifkarim/movie-site-sample)

## Steps

Some common initials steps are listed here

- Firstly, I have created this repository in git for this project and cloned it to my local machine
- Then I have run `npx create-react-app movie-gold-v1` command to create a boilerplate project for React
- This steps has taken a good amount of time. Already `Node JS(v20.10.0)` is installed in my system.
- Now., it is time to delete some files and update settings according to the tutorial
- From `movie-gold-v1/src`
  - have deleted`App.test.js` file
  - From `package.json` deleted
    ```sh
    "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
      ]
    }
    ```
  - From `index.js` file deleted content related to `reportWebVitals`
- Now have to install few NPM packages which will be integrated to the application
  - To make easy HTTP requests: `npm install axios`
  - To enable bootstrap: `npm install bootstrap`
  - Allow to use bootstrap related components: `npm i react-bootstrap`
  - Allow easy install of font awesome icons: `npm i @fortawesome/react-fontawesome`
  - Second fontawesome package: `npm i @fortawesome/free-solid-svg-icon`
  - Allow to use react player: `npm i react-player`
  - Map the root to the components: `npm i react-router-dom`
  - Enable carousel: `npm install @mui/material @emotion/react @emotion/styled`
  - To use the material UI carousel component: `npm install react-material-ui-carousel`