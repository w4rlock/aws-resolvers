[![npm version](https://badge.fury.io/js/aws-resolvers.svg)](https://badge.fury.io/js/aws-resolvers)
[![npm downloads](https://img.shields.io/npm/dt/aws-resolvers.svg?style=flat)](https://www.npmjs.com/package/aws-resolvers)

### Installation
```bash
$ npm i -E aws-resolvers
```
### Node Config Example
```javascript
// config/default.js
const { asyncConfig } = require('config/async');
const { SSM } = require('aws-resolvers')

module.exports = {
  mysql: {
    passwd: asyncConfig(SSM.getParameterValue('us-east-1', '/path/to/secret'))
  }
}

```


