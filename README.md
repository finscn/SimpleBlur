SimpleBlur
==========

a  blur-effect library  for HTML5 canvas


======

example:

```
var blur= new Blur({
    radius: 20,
    gaussian : true,
});
blur.init();

var img =  obj ; // a  Image or Canvas 
var blurImg = blur.blurRGBA(img, null, true);

```