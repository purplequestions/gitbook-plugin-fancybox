gitbook-plugin-fancybox
=======================

A gitbook plugin to show image by graceful jQuery fancy box

[DEMO](http://read.lingyu.wang/webkit-core/webkit-arch-and-module.html)

##Install

```shell
$npm install --save gitbook-plugin-fancybox
```

##Usage

Add the plugin to your `book.json` like this:

```javascript
{
    "plugins": ["fancybox"]
}
```

##Options

```javascript
"pluginsConfig": {
    "fancybox": {
      //your fancybox config here
    }
}
```

defaultConfig:

```javascript
{
  helpers: {
    buttons: {}
  }
}
```

##License

The MIT License (MIT)

Copyright (c) 2015 Lingyu Wang

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
