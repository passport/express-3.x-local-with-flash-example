This example demonstrates how to use [Express](http://expressjs.com/) 3.x and
[Passport](http://passportjs.org/) to authenticate users using a username and
password with [form-based authentication](https://en.wikipedia.org/wiki/HTTP%2BHTML_form-based_authentication).
Any errors that occur during authentication are displayed to the user using
the [flash](https://github.com/jaredhanson/connect-flash).  Use this example as
a starting point for your own web applications.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:passport/express-3.x-local-example.git
$ cd express-3.x-local-example
$ npm install
```

Start the server.

```bash
$ node server.js
```

Open a web browser and navigate to [http://localhost:3000/](http://127.0.0.1:3000/)
to see the example in action.  Log in using username `jack` and password `secret`.
