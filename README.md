**Javascript bookmarklet for Sci-Hub**

The [Javascript code](scihub_bookmark.js) will insert `.sci-hub.cc` into the URL of your current tab and reload the page.

To use, create a new bookmark and paste the Javascript code into the address box. If you do not have access to a paper, clicking the bookmark will reload the page using Sci-Hub.

```html
javascript:location.href = location.origin.replace(/^https/, 'http') + '.sci-hub.tw' + location.pathname + location.search
```

Or just drag this link to your bookmark bar: **<a href="javascript:location.href = location.origin.replace(/^https/, 'http') + '.sci-hub.tw' + location.pathname + location.search">scihub</a>**.