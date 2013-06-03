### goo.gl url shortener for compoundjs ###
Just a simple wrapper for https://github.com/kaimallea/node-googl for compoundjs

1. Add to autoload.js
2. From there you can access node-googl methods in controller

```javascript
    // Shorten a long url and output the result
    compound.googl.shorten('http://www.google.com/', function (shortUrl) {
        console.log(shortUrl);
    });

    // Set a developer key (see http://goo.gl/4DvFk for more info.)
    compound.googl.setKey('aBcDeFGhIjKLMnOPqRsT');


    // Expand a goo.gl url and output the result
    compound.googl.expand('http://goo.gl/fbsS', function (longUrl) {
        console.log(shortUrl);
    });
```
