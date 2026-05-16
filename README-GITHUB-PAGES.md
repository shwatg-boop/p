# GitHub Pages Upload Notes

This version embeds all visible website images directly into the HTML files as Base64 data images.

That means the main hero image **and product/catalog images** should display even if GitHub Pages has trouble resolving the `assets/` folder paths.

Upload everything in this folder to your repository root:

```
index.html
microlots.html
lamjung.html
gulmi.html
kaski.html
farm-map.html
green-beans.html
story.html
order.html
styles.css
script.js
.nojekyll
assets/   optional backup copies
```

Important: do not upload the ZIP itself. Extract it first, then upload the extracted files.

If GitHub still shows an older version, hard refresh:
- Windows: Ctrl + Shift + R
- Mac: Cmd + Shift + R
