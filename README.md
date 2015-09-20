proto2ts
================

[Proto2TypeScript](https://github.com/SINTEF-9012/Proto2TypeScript) repository fork with the purpose of supporting the usage of this module in according with task runner tools such as Gulp
or Grunt

This tool generate TypeScript definitions for your Protocol Buffers models, when you use the excellent [ProtoBuf.js](https://github.com/dcodeIO/ProtoBuf.js/) library.

### Usage
```js
// Install
npm install proto2ts -save-dev

// Get protobuf Json declaration 
var protobufJsonString = '{ ... }'

// Generate TypeScript type declarations
var proto2ts = require('proto2ts')
var tsDeclarationsString = proto2ts(protobufJsonString)

// Save generated TypeScript type declarations
...

```

### Why ?

Because intelligent code completion is cool :-)

![](http://i.imgur.com/evVnEM5.png "Example in sublime text")

### Licence

The source code of this tool is licenced under the MIT License.
