
#Optimizations performed

##/index.html
* Resized img/thumb4.jpg to a proper thumbnail size
* Minified and inlined CSS
* Added 'async' attribute to non-critical JS code (Google Analytics)
* Added cache-control META tag

## /views/js/main.js

* Optimized changePizzaSizes() by moving var calculations outside loop
* Optimized updatePositions() by creating elements array and changing posX using CSS instead of direct DOM manipulation
* Performed PageSpeed tests and optimizations

## /views/css/style.css
* added hack to enable GPU acceleration and enabled elements to render on their own composite layer
