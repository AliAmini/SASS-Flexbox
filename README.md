SASS-Flexbox
============
You can use this file if you want include your flexbox with all(3) syntaxes.

This file can better your life!

# How To Use?
For example if you want write: 
```
display: -webkit-box;      /* OLD - iOS 6-, Safari 3.1-6 */
display: -moz-box;         /* OLD - Firefox 19- (buggy but mostly works) */
display: -ms-flexbox;      /* TWEENER - IE 10 */
display: -webkit-flex;     /* NEW - Chrome */
display: flex; 
```
 in css, just write `@include display-flex;` or for write: 
 ```
-webkit-box-pack: start; 
-moz-box-pack: start;
-ms-flex-pack: start;
-webkit-justify-content: flex-start;
justify-content: flex-start;
 ```
 in css, just write `@include justify-content-flex-start`.