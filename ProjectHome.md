# Rounded corner HTML elements using CSS3 #
This is a behavior htc file for Internet explorer to make CSS property " border-radius " work on all browsers.
At present, all major browsers other than IE shows curved corner by adding 4 lines of css

_.curved {
-moz-border-radius:10px; /**Firefox**/
-webkit-border-radius:10px; /**Safari and chrome**/
-khtml-border-radius:10px; /**Linux browsers**/
border-radius:10px; /**CSS3**/
}_

Now adding the htc with one more line of css will make the curve work in IE browsers also
behavior:url(border-radius.htc)

More details are on http://www.htmlremix.com/css/curved-corner-border-radius-cross-browser