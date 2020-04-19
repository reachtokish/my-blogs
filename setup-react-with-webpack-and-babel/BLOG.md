# Setup react with webpack and babel

We generally use [create-react-app (CRA) CLI]() to generate a basic react application with zero configuration. That's cool because you don't have know [babel]() or [webpack]() or even what's going on under the hood of CRA. But what if you also want to setup your own configuration and add babel and webpack however you want? Here comes setup babel and webpack from yourself and know the basic configuration of those tools.

So we will setup a basic react application with webpack and babel. The fun part is lastly we will see how [cors](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) issue can be solved using webpack devServer configuration.

If you don't have any idea of what is CORS issue then I would suggest you to go through [this link](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) once.

## Table of contents
- Setup of basic `webpack` config for a basic react application
- Setup of basic `babel` config for a basic react application
- Basic folder structure for a react project
- Setup a basic nodeJs backend
- Resolve `cors` issue

So without any further readings we will dive into the course of content

First we will create a folder called `my-react-app` and navigate inside that folder in our command line tool like CMD or Terminal.

Then from there we will run the below command to generate a basic package.json file

```
npm init -y
```

or

```
npm int
```

and follow the installation instruction.

Then you will see a package.json file has been created inside the `my-react-app` folder.

Now we will install required packages for webpack first by running the following command

```
npm install -D clean-webpack-plugin css-loader file-loader html-webpack-plugin style-loader webpack webpack-cli webpack-dev-middleware webpack-dev-server
```

> You can check what individual plugin does exactly from the official [webpack website]().

Now you can see 