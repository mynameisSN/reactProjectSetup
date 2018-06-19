# reactProjectSetup

## Babel

```
npm install --save-dev babel-core@6.26.3 babel-cli@6.26.0 babel-preset-env@1.7.0 babel-preset-react@6.24.1

```
> babel-core is the main babel package — We need this for babel to do any transformations on our code. babel-cli allows you to compile files from the command line. babel-preset-env and babel-preset-react are both presets that transform specific flavors of code — in this case, the env preset allows us to transform ES6+ into more traditional javascript and the react preset does the same, but with JSX instead.


> In the project root, create a file called .babelrc. Here, we’re telling babel that we’re going to use the env and react presets.


## Webpack

save these as dev dependencies: 

```
npm install --save-dev webpack@4.12.0 webpack-cli@3.0.8 webpack-dev-server@3.1.4 style-loader@0.21.0 css-loader@0.28.11 babel-loader@7.1.4

```

> Webpack uses loaders to process different types of files for bundling. It also works easily alongside the development server that we’re going to use to serve our React project in development and reload browser pages on (saved) changes to our React components. In order to utilize any of this though, we’ll need to configure Webpack to use our loaders and prepare the dev server.

## start project

```
npm start

```