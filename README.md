# install
$ npm i ez-snow.js

# How to use?  

Demo here:  
<https://jimmyy512.github.io/ez-snow.js-demo>

import ezSnow from 'ez-snow.js';   

* @param {string} appendDomName - 下雪要插入的DOM.  
* @param {string} srcPath - 圖片路徑.  
* @param {number} bgWidth - 產生後的圖片寬度.  
* @param {number} bgHeight - 產生後的圖片高度.  

new ezSnow("body","your image path",30,20).init();
