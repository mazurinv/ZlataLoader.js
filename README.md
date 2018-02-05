# ZlataLoader.js
ZlataLoader is a tiny javascript library to draw loaders for web sites

## DEMO PAGE
[link](http://mazurinv.ru/demo/ZlataLoader/)
## Installation

just include ZlataLoader.js to your page
```
<script src="scripts/ZlataLoader.js"></script>
```

## Usage
To init instance of Zlata Loader you must add DIV element to your page with ID param set.
Let the ID be #loader1.
```
<div id="loader1"></div>
```
And in JS part of your code:
```
    new ZlataLoader({
         id: 'loader1',
         imgSrc: "plane.png",
         mode: 'double',
         radius: 90,
         speed: -2,
         lineColor: '#8bfaa8',
         lineWidth: 4,
         imageWidth: 78
     });
```
Where:
```
id              - element ID in DOM (#loader1 for example) 
radius          - radius of animation
lineWidth       - width of the circle line
lineColor       - color of the circle line
mode            - type of animation (available types are: single, double, picture)
imgSrc          - source of image to animate
imageWidth      - width of image in pixels (64 by default)
speed           - speed parameter. if positive - motion will be clockwise
```


Copyright 2018 Vladimir Mazourin