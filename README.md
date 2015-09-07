# FrankerFaceZ UserScript/Bookmarklet
If you would rather try out FrankerFaceZ as a bookmarklet, copy the URI below:

```javascript
javascript:(function(document){'use%20strict';(document.head||document.getElementsByTagName('head')[0]).appendChild(document.createElement('script')).src='//cdn.frankerfacez.com/script/script.min.js';})(document);
```

Originally, [FrankerFaceZ](http://www.frankerfacez.com/) had [an officially supported UserScript](http://userscripts-mirror.org/scripts/show/167158) written by the extension's creator, [Dan Salvato](http://www.twitch.tv/dansalvato/profile), but now that the project has moved to its own CDN, the referenced script is outdated; the style used in both the bookmarklet and the UserScript is based on code used by the extension's current maintainer, [Mike (SirStendec)](http://www.twitch.tv/sirstendec/profile), to test development on Microsoft Edge in anticipation for that browser's upcoming support for Chromium-style extensions.
