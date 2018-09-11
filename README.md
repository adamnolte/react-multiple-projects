This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## How to Run locally
1. `npm run serve`

## How to Build
1. `npm run build`
2. Files will be placed in the build folder
3. React and react-dom will not be included in the bundle and will need to be included externally

## How To Add New Webpart

1. Add new folder under src/webparts
    * Create index.js that uses ReactDom.render
    * Reference existing index.js
    * Create your main App.js
2. Add your entry to config/paths.js
3. Add your entry to config/webpack.config.{dev/prod}.js
