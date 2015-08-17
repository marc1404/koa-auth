# koa-auth-jwt
[![NPM](https://nodei.co/npm/koa-auth-jwt.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/koa-auth-jwt/)
  
[![Build Status](https://travis-ci.org/marc1404/koa-auth.svg)](https://travis-ci.org/marc1404/koa-auth)
[![Code Climate](https://codeclimate.com/github/marc1404/koa-auth/badges/gpa.svg)](https://codeclimate.com/github/marc1404/koa-auth)
[![Test Coverage](https://codeclimate.com/github/marc1404/koa-auth/badges/coverage.svg)](https://codeclimate.com/github/marc1404/koa-auth/coverage)
  
[![dependencies](https://david-dm.org/marc1404/koa-auth.svg)](https://david-dm.org/marc1404/koa-auth)
[![dev-dependencies](https://david-dm.org/marc1404/koa-auth/dev-status.svg)](https://david-dm.org/marc1404/koa-auth#info=devDependencies)
  
## Installation
```
$ npm install koa-auth-jwt
```
  
## Usage
```javascript
// ...  
var auth = require('koa-auth-jwt');
  
app.use(auth({
	secret: process.env.SECRET,
	token: 'X-Auth-Token' // optional
});
```
  
## Test
```
$ npm install -g mocha  
$ mocha
```
  
## License
**MIT**
