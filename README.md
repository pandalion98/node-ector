# ector

ECTOR is a learning chatterbot. This is its Node.js version.
[![Build Status](https://secure.travis-ci.org/parmentf/node-ector.png)](http://travis-ci.org/parmentf/node-ector)

## Getting Started
Install the module with: `npm install ector`

```javascript
var Ector = require('ector');
var ector = new Ector();
ector.addEntry("Hello ECTOR!");
var response = ector.generateResponse();
console.log(response.sentence);
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [mocha](http://visionmedia.github.com/mocha/).

## Release History

* 2013/01/05: version 0.1.0: first release

Warning: this is a work in progress.

## License
Copyright (c) 2012 François Parmentier  
Licensed under the MIT license.
