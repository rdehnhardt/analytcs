# analytcs

Javascript for web analytcs

# Instalation

Put dist/analytcs.js or dist/analytcs.min.js in a public url and change the endPoint.

In your HTML put the code 

```
var _px = _px || [];
_px.push(['_setAccount', 'accountName']);

(function() {
    var px = document.createElement('script');px.src = 'http://your.public.url.com/analytcs.js';px.type = 'text/javascript';px.async = true;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(px, s);
})();
```
