# Seagull BnB

An accomodation listing and booking site.

## MVP User Stories

```
As a user
So that my property can be seen
I want to create a property listing on Seagull BnB
```

```
As a user
So I my property will be listed
I want to enter my property name
```

```
As a user
So that my property will be appealing
I want to give my property a description
```

```
As a user
so that other users can see my property
I want my property listing to be displayed
```

```
As a user
so that I can holiday \o/
I want to book a property
```

```
As a user
So that my property is not double-booked
I want my property to be unavailable once booked
```

## Technology

- Node.js
- [NPM](https://www.npmjs.com/) package management system
- [Node Express](https://expressjs.com/) web framework for node.js
- vanilla JavaScript
- JQuery
- semantic HTML
- CSS
- [Heroku](https://www.heroku.com/)
- [Jasmine](https://jasmine.github.io/setup/nodejs.html)
- ES Lint
- Cypress


## Set Up

Install Node.js
Install NPM

Edit the `./package.json` file so that the `test` path reads:

```
"test": "./node_modules/jasmine/bin/jasmine.js"
```

### Running Tests

Use the npm command in the command line to run Jasmine:

```shell
$ npm test
```

Integration tests are located in `./cypress/integration`.

Install Cypress:
```shell
$ npm install cypress --save-dev
```

Open Cypress with the command below to run end-to-end tests:

```shell
$ npx cypress open
```

![](https://thepracticaldev.s3.amazonaws.com/i/bku3lxtqjklrlx6d9nwx.png)


### Note

.bak contains back-up files, no peeking.
