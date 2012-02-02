# express-ajax [![Build Status](https://secure.travis-ci.org/konteck/express-ajax.png)](http://travis-ci.org/konteck/express-ajax)

Automatically AJAX requests handling middleware for Express framework

## Installation

```
npm install express-ajax
```

## Usage

To be able return only your view without it's layout, in case if request
came through XmlHttpRequest, just include this middleware in your your Express
configuration section. No need to do additional changes in your code.

```javascript

app.configure(function() {
  app.use(require('express-ajax'));
});

```

That's it!