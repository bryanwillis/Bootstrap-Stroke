## Welcome to Bootstrap Stroke Icons project
Bootstrap stroke icons (BSS) is free of charge vector icon set created for famous [Twitter Bootstrap project](https://github.com/twbs/bootstrap). Glyphicon set is used by default and Bootstrap version 3.2 contains 200 icons. BSS uses stroke style and contains 205 fully compatible icons.

 
## Live example
Just check this <a href="http://highrobotics.com/we-did-it/web/bootstrapstrokeicon.aspx" target="_blank">live example</a> of the icons.
<br/>
<a href="http://highrobotics.com/we-did-it/web/bootstrapstrokeicon.aspx" target="_blank">
<img src="http://www.highrobotics.com/media/images/bss_github.jpg" alt="Bootstrap stroke icons" /></a>

## How to enable

### Simple and fast solution with CDN 

We already prepared for you ready to use files.
After Bootsrap installation replace file refererence from `bootstrap.min.css` to corrected one at [jsdelivr](http://www.jsdelivr.com/#!bootstrap-stroke) in the ```<HEAD>``` section of your page. To use Bootsrap 3.2.0 with Bootsrap-Stroke font just add reference

```
<link href="//cdn.jsdelivr.net/bootstrap-stroke/1.0.0/css/bss-bootstrap.3.2.0.min.css" rel="stylesheet" type="text/css">
```

This is it!

* ```bss-bootstrap.3.2.0.min.css``` is a based on ```bootstrap.min.css``` and differs only in font reference.

* CDN is provided by [jsdelivr](http://www.jsdelivr.com) - a file hub with fast access from any world point.

### Advanced solution

For experienced users we provide ```.less``` files for private customization. After downloading Twitter Bootstrap source files make changes to the next files in ```less``` folder:

* Copy ```icons.less``` file from our source to Bootstrap less folder.

* Inside Bootstrap project edit ```bootstrap.less``` file:   
  remove or comment line ```@import  "glyphicons.less";```   
  include line ```@import "icons.less";```

* Edit ```variables.less``` file and change Iconograpfy variables to
  ```
  //** Load fonts from this directory.
  @icon-font-path:          "../fonts/";
  
  //** File name for all font files.
  @icon-font-name:          "bootstrap-stroke"; // default: "glyphicons-halflings-regular";
  
  //** Element ID within SVG icon file.
  @icon-font-svg-id:        "bootstrap-stroke"; // default: "glyphicons_halflingsregular";
  
  //** Font family name
  @icon-font-family:        'Bootstrap stroke'; // default: "Glyphicons Halflings";
  
  //** Prefix is used in icons class declaration 
  // <span class="glyphicon glyphicon-star">
  // <span class="bss bss-star">
  @icon-font-prefix:        bss; // default: glyphicon;
  ```

Customize on your needs the font variables and then compile ```bootsrap.less``` to css file.

## How to use
Applying css file from jsdelivr CDN you make code valid as in Twitter Bootsrap project. So there is no need in any other changes, for example, using glyphicon-star is same: ```<span class="glyphicon glyphicon-star" />```.

In case of custom prefix like ```@icon-font-prefix: bss``` use ```<span class="bss bss-star" />```. 

Read more about icon applying at [Bootrap Help](http://getbootstrap.com/components/).

## License
Code: [MIT](http://opensource.org/licenses/MIT)   
Fonts: [Creative Common 2.0](http://creativecommons.org/licenses/by/2.0/)

## Support or Contact
Having trouble with icons or want to say hi? Contact us via team@highrobotics.com.

