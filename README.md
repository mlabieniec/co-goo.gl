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
### License ###
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
