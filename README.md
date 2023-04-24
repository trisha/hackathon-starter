Table of Contents
-----------------
- [About](#about)
- [Getting Started](#getting-started)
- [License](#license)

About
-------------
If you've ever had a heated or emotional argument over text, first of all, don't. At the very least communicate over voice. But, if you do find yourself in written situations where your emotions or ego get the best of you, and you want to resolve your conflict, AI can help you say things that are still try to how you feel, but in a way that's tactful and will make the other person feel heard and receptive to your feelings.

How this app will work:

1. Input text messages from other person, demarcated by `<text></text>` tags. (Future: upload screenshots and use OCR to transcribe to text)
2. Input how you really feel and why they were wrong and why you feel the way you feel
3. Select which tone you want your response to be in: 'cool n collected' 'apologetic aphrodite' 'sassy betch' '"mature for her age"' (lashes out emotionally but will otherwise be reasonable)

Prerequisites
-------------

- [Node.js 10+](http://nodejs.org)

Getting Started
---------------

The easiest way to get started is to clone the repository:

```bash
# Clone repo
git clone git@github.com:trisha/text-fight-helper.git

# Change directory
cd text-fight-helper

# Install NPM dependencies
npm install

# Then simply start your app
node app.js
```

**Warning:** If you want to use some API that needs HTTPS to work (for example Pinterest or Facebook),
you will need to download [ngrok](https://ngrok.com/).
You must start ngrok after starting the project.

```bash
# start ngrok to intercept the data exchanged on port 8080
./ngrok http 8080
```

Next, you must use the https URL defined by ngrok, for example, `https://hackaton.ngrok.io`

**Note:** I highly recommend installing [Nodemon](https://github.com/remy/nodemon).
It watches for any changes in your  node.js app and automatically restarts the
server. Once installed, instead of `node app.js` use `nodemon app.js`. It will
save you a lot of time in the long run, because you won't need to manually
restart the server each time you make a small change in code. To install, run
`sudo npm install -g nodemon`.

License
-------

The MIT License (MIT)

Copyright (c) 2014-2022 Sahat Yalkabov

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


