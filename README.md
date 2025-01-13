# Myanmar Keyboard Bookmarklet

## How to use

- Drag <a href="javascript:void%20function(){e=document.createElement(%22script%22),e.type=%22text/javascript%22,e.onload=()=%3E{loadKeymanWebBookmarklet(%22sil_myanmar_my3%22,%22my%22)},e.src=%22https://r.keymanweb.com/code/bookmarklet_loader.js%22,document.body.appendChild(e),document.addEventListener(%22keyup%22,function(a){a.metaKey%26%26%22Space%22===a.code%26%26(a.preventDefault(),document.querySelector(%22%23kmwico%20img%22).click())})}();">this link</a> to you bookmark bar OR create a bookmark with the following code.

- Click the bookmark when on web pages.
- Toggle between the original keyboard and the Myanmar keyboard using **Meta (Windows Key) + Space**.

## Code

```js
javascript:void%20function(){e=document.createElement(%22script%22),e.type=%22text/javascript%22,e.onload=()=%3E{loadKeymanWebBookmarklet(%22sil_myanmar_my3%22,%22my%22)},e.src=%22https://r.keymanweb.com/code/bookmarklet_loader.js%22,document.body.appendChild(e),document.addEventListener(%22keyup%22,function(a){a.metaKey%26%26%22Space%22===a.code%26%26(a.preventDefault(),document.querySelector(%22%23kmwico%20img%22).click())})}();
```

## Known Bugs

- Slow to load.
- The keyboard may sometimes lag over time.
- The font in the text box changes.
- Some fonts cannot display Myanmar Unicode characters correctly.
- The Meta key may become disabled after use. (Refreshing the web page may resolve this issue.)

## Credit

- [Keyman](https://keyman.com)

**_Disclaimer: The bookmarklet loads scripts from Keyman, and you are solely responsible for trusting Keyman's code._**
