Jensz12 Theme for Google Chrome/Chromium
============

<br>Find the release in the webstore here: https://chrome.google.com/webstore/detail/jensz12/lfcfgfboglfhoianmebpbemgbdepglgm</br>
<br>Or here if you want to compile it yourself: https://github.com/Jensz12site/Chrome-theme/releases</br>

<h3>Why is <code>"minimum_chrome_version": "18"</code>?</h3>
Beacuse Chrome 18 and older dosn't support <code>"manifest_version":2</code>

<h1>How to compile a Chrome theme (In Chrome/Chromium):</h1>

* Download the newest release of the theme here: https://github.com/Jensz12site/Chrome-theme/releases
* Bring up the Extensions management page by going to this URL:
chrome://extension.
* Ensure that the "Developer mode" checkbox in the top right-hand corner is checked.
* Click the Pack extension button. A dialog appears.
* In the Extension root directory field, specify the path to the extension's folder—for example, C:\myext. (Ignore the other field; you don't specify a private key file the first time you package a particular extension.)
* Click Package. The packager creates two files: a .crx file, which is the actual extension that can be installed, and a .pem file, which contains the private key.
* https://developer.chrome.com/extensions/packaging

<h1>Is something broken?</h1>
* https://developer.chrome.com/extensions/manifest
* https://developer.chrome.com/extensions/themes
* https://code.google.com/p/chromium/wiki/ThemeCreationGuide
