# graphql-test

This is a small piece of codes to show making graphql testing service and learn basic graphql.

# Steps to build application 

1. make a new directory
```
mkdir graphql-test && cd "$_"
```

2. initialize node

```
npm init
```
  _you can skip all options with default(empty)_

3. install all depentancy modules
 - [express](https://www.npmjs.com/package/express) : minialized webframework
 - [express-graphql](https://www.npmjs.com/package/express-graphql) : graphql service module to testing graphql which works on express
 - [graphql](https://www.npmjs.com/package/graphql) : graphql reference implementation for javascript
```
npm i express express-graphql graphql
```

4. (optional) add automatic restarting applicatio helper [nodemon](https://www.npmjs.com/package/nodemon)
```
npm i --save-dev nodemon
```

5. run application
```
npm run devstart
```

6. with your web browser, connect application and wish a good luck! :+1:
```
http://localhost:5000/graphql?
```
