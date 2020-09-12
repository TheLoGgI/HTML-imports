# HTML-imports

Easy HTML imports from HTML documents

## Install
Put the script tag in the head of your HTML document
so the script can load toghter with the html.

```
  // Insert in head with async or defer attribute
  <script src="imports.js" async></script> 

  <script src="imports.js" defer></script>
```

## How To Use
Use a div (or any other tag) with an empty import attribute followed by a href attribute assigned with the location of your HTML file.

```
 <div import href="./pages/content.html"></div>
```

## Issues
This script takes use of the DOMParser API which is not support by some browers.
Check caniuse.com for support https://caniuse.com/?search=domparser
