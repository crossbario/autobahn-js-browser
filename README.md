# AutobahnJS "Built"

This repository contains the built and released **browser** versions of [AutobahnJS](https://github.com/tavendo/AutobahnJS) ready for use in your project.

## Usage

Copy the `autobahn.min.js` file to your Web server. Done.

You can also use the `autobahn.min.jgz` compressed version, but then need to make sure your Web server sets the required HTTP headers on responses delivering the file to a browser:

```
Content-Type: application/javascript
Content-Encoding: gzip
```

## Using with Bower

Install with [bower](http://bower.io/):

	bower install autobahn

Add a `<script>` tag to your `index.html`:

	<script src="/bower_components/autobahnjs/autobahn.min.js"></script>

To list available versions of AutobahnJS:

	bower info autobahn
