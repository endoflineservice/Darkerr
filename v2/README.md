# Darkerr
A darker theme for Sonarr &amp; Radarr

# Installation
* Download one of these add-ons for your browser
  * Stylus (recommended): [Chrome](https://chrome.google.com/webstore/detail/clngdbkpkpeebahjckkjfobafhncgmne), [Firefox](https://addons.mozilla.org/firefox/addon/styl-us/), or [Opera](https://github.com/schomery/stylish-chrome/).
  * Osprey: [Chrome](https://chrome.google.com/webstore/detail/osprey/ekjapccimkannnfgcnnoajhfdglobgak).
  * Stylish: [Chrome](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/), and [Opera](https://addons.opera.com/en-gb/extensions/details/stylish/).
* Go [userstyles.org](https://userstyles.org/styles/142759/darkerr-a-darker-theme-for-sonarr-radarr), and click on "Install Style" button.
* Done! From now on it will automatically update.

You do not use the default ports (8989 for Sonarr and 7878 for Radarr)?
If so, just change the string in the settings, from:
```
((http(s?))://)?[-A-Za-z0-9+&@#/%?=~_|!:,.;]+(8989|7878)+(.*)
```
to:
```
((http(s?))://)?[-A-Za-z0-9+&@#/%?=~_|!:,.;]+(your sonarr port|your radarr port)+(.*)
```
(Note: for each update, this change must be done again)
