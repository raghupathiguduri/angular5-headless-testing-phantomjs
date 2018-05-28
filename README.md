# Run Angular unit tests with PhantomJS headless browser

## Install and configure PhantomJS
* `npm install --save-dev karma-phantomjs-launcher`
* Add PhantomJS to your karma.conf.js
* Enable all 'import core-js/es6/...' in the top of polyfills.ts file

## Install and configure unit tests result report file
* `npm install --save-dev karma-htmlfile-reporter`
* Add tests result report configuration to your karma.conf.js

## Run Unit Tests:
* Run `ng test` to run tests in all browsers (Chrome and PhantomJS)
* Run `ng test --browsers PhantomJS --watch false` to run tests in PhantomJS headless browser only
* Run `ng test --browsers Chrome` to run test in Chrome browser only
* Unit tests result report should be create in root folder TestResults
