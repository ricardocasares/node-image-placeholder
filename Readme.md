Image-Placeholder
================

A ready web app to serve images for your image placeholder.
Image placeholder can be requested with following ways
(assuming app is deployed to example.com):

* A 300x300 image:
  `<img src="http://example.com/300">`

  ![](https://github.com/gedex/node-image-placeholder/raw/master/screenshots/300x300.png)

  or
  `<img src="http://example.com/300x300">`
* A 400x320 image with text color #fff and background color #ff0000:
  `<img src="http://example.com/400x320/fff/ff0000">`
  
  ![](https://github.com/gedex/node-image-placeholder/raw/master/screenshots/400x320-fff-ff0000.png)

## Demo Instances

* [http://image-placeholder.jit.su/](http://image-placeholder.jit.su/)
* I couldn't get the app run on heroku. Seems the canvas workaround doesn't give me a luck.
  Let me know if you can get the app running on heroku.


## Running locally

Before install dependencies, make sure you have [Cairo](http://www.cairographics.org/) installed.
[Node-canvas](https://github.com/LearnBoost/node-canvas/) depends on Cairo. Install dependencies:
````bash
npm install
````

Run image-placeholder:
````bash
node app.js
````

## Deploy to heroku

Later on this.

## Deploy to [nodejitsu](http://nodejitsu.com/)

This app is ready to deploy to nodejitsu. Make sure you change `subdomain` key
in `package.json`, or it will prompt you that the domain already exist. Make
sure you have nodejitsu account and [jitsu CLI](http://github.com/nodejitsu/jitsu) installed.
To deploy go to your cloned-image-placeholder repo and run:

````bash
jitsu deploy
````

## License - "MIT License"

Copyright (c) 2012 Akeda Bagus &lt;admin@gedex.web.id&gt;

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
