
# @darkcriminal/redwap-scraper

A simple Redwap Scraper that srapes/gets video data and downloadable video source and returns a promise/JSON Object result.

# How To Install?
```
npm i @darkcriminal/redwap-scraper
```

# Require to export function
```js
//CommonJS
const { redwaprandom } = require('@darkcriminal/redwap-scraper');
```

## Simple Usage
### usage of `redwaprandom()`
```js
const { redwaprandom } = require('@darkcriminal/redwap-scraper');

async function result() {
    const data = await redwaprandom("squirt")
    console.log(data)
}
result()
```