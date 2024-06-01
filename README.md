
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
## Sample Sucess Responses
```js
{
  status: true,
  creator: 'Nimesh Official',
  result: {
    title: 'Tanner Mayes fucks missionary style after 69 style oral sex',
    image: 'https://img.redwap-cdn.com/488/488470/488470_320x180.jpg',
    url: 'https://www.redwap.me/videos/488470/tanner-mayes-fucks-missionary-style-after-69-style-oral-sex/',
    dllink: 'https://video.redwap-cdn.com/key=6lWN7qVzxG10vfjwAs12Xw,end=1717225631,limit=1/download2=[redwap.me] tanner_mayes_fucks_missionary_style_after_69_style_oral_sex.mp4/488470_video.mp4'
  }
}
```
