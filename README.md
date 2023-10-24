>npm install webpack webpack-cli --save-dev
>npm install --save-dev html-webpack-plugin
>npm install --save-dev html-loader
> npm i -D webpack-dev-server

> npm install --save-dev style-loader css-loader
> npm install copy-webpack-plugin --save-dev

// mejorar el js
https://babeljs.io/setup#installation

npm install --save-dev babel-loader @babel/core
 
rules: [
      {
        test: /\.m?js$/,
        exclude: /node_modules/,
        use: {
          loader: "babel-loader",
          options: {
            presets: ['@babel/preset-env']
          }
        }
      }

      
npm install @babel/preset-env --save-dev