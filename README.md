# AutobahnJS - Browser build

This repository contains the **built** and released **browser** versions of [AutobahnJS](https://github.com/crossbario/autobahn-js) ready for use in your project.

---


## Usage

## Using plain

Copy the **[autobahn.min.js](autobahn.min.js)** file to your Web server. Done.

> You can also use the **[autobahn.min.jgz](autobahn.min.jgz)** compressed version, but then need to make sure your Web server sets the required HTTP headers on responses delivering the file to a browser:
```
Content-Type: application/javascript
Content-Encoding: gzip
```

---


## Using with npm

The browser version is published to npm under the name **[autobahn-browser](https://www.npmjs.com/package/autobahn-browser)**. Install with:

```console
npm install autobahn-browser
```

> Note: the NodeJS version of Autobahn continues to be published under the name **[autobahn](https://www.npmjs.com/package/autobahn)**.

---


## Using with Bower

Install with [bower](http://bower.io/):

```console
bower install autobahn
```

Add a `<script>` tag to your `index.html`:

```html
<script src="/bower_components/autobahnjs/autobahn.min.js"></script>
```

To list available versions of AutobahnJS:

```console
bower info autobahn
```

---
