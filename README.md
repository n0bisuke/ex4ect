#express4 template for ect

## How to Use

### install and edit
```
$ git clone git@github.com:n0bisuke/ex4ect.git
$ cd ex4ect

$ vim package.json
L2 "name": "ex4ect",
↓
L2 "name": "myappname",

$ vim bin/www

L2 var debug = require('debug')('ex4ect');
↓
L2 var debug = require('debug')('myappname');

$ npm install

$ DEBUG=myappname ./bin/www
  myappname Express server listening on port 4444 +0ms
```

### access

http://localhost:4444

![](http://i.gyazo.com/a020f4788a9ecae06f092681be4a47d1.png)
