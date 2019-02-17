This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### How to deploy to github pages - easy without CI

    npx create-react-app <app-name>
    npm i gh-pages or yarn add gh-pages

add the following to package.json

    "homepage": "https://<username>.github.io/<app-name>/",

    "predeploy": "yarn run build",
    "deploy": "gh-pages -d build"

then run with yarn or npm
  
 yarn run deploy

Remember to add github pages in github repository and select gh-pages branch
