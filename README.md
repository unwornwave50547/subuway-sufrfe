# hSSS unblocaaa

Evade internet censorship!

The original nodeunblocker.com is gone, but it's now easier than ever to deploy your own copy.

[![Deploy to Bluemix](https://cloud.ibm.com/devops/setup/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/nfriedly/nodeunblocker.com)
[![Deploy to AWS](https://oneclick.amplifyapp.com/button.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/nfriedly/nodeunblocker.com)
[![Deploy to Cyclic](https://deploy.cyclic.sh/button.svg)](https://deploy.cyclic.sh/)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fnfriedly%2Fnodeunblocker.com)

## Now with YouTube support (sort of)

I went ahead and activated the [youtube example](https://github.com/nfriedly/node-unblocker/blob/master/examples/youtube/youtube.js), it replaces youtube.com video pages with a custom page that just streams the video (but actually works). 

To disable it just add `//` to the beginning of [this line of code in app.js](https://github.com/nfriedly/nodeunblocker.com/blob/5355bbfa8cfe2b5d2e6e5aae41ea21936a3be9a5/app.js#L59) like so:

```js
//        youtube.processRequest
```

## Running the website on your computer

1. Install [node.js](http://nodejs.org/)
2. [Download the code](https://github.com/nfriedly/nodeunblocker.com/archive/master.zip)
3. Unzip it
4. Open up a terminal/command line
5. `cd` into the directory
6. Run `npm install` to grab the dependencies.
7. Run `npm start` to start the server. It should spawn a new instance for each CPU core you have.
 thank you god nfriedly your codeing is soo goodness

This project is released under the terms of the [GNU Affero General Public License version 3](https://www.gnu.org/licenses/agpl-3.0.html).

All source code is copyright [Nathan Friedly](http://nfriedly.com/).
