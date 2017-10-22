## Getting started with Node and Puppeteer on Ubuntu
### Install nvm and source the file .bashrc:
- curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
- source ~/.bashrc

### Install node and set the default node version on your shell:
- nvm install v8.4.0
- nvm alias default v8.4.0

### Create a project and a sample index.js file
- mkdir helloworld-pupeteer
- cd helloworld-pupeteer/
- npm init
- npm install puppeteer
- echo "node_modules" > .gitignore
- touch index.js
(Then, use the sample code for your index.js):

```sh
const puppeteer = require('puppeteer');
(async () => {
  const browser = await puppeteer.launch({headless: false});
  const page = await browser.newPage();
  await page.goto('https://example.com');
  await page.screenshot({path: 'example.png'});

  browser.close();
})();

```
### Run the project:
- node index.js

### Documentation
https://github.com/GoogleChrome/puppeteer/blob/master/docs/api.md#pagehoverselector
