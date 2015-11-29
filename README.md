## Welcome to Bootstrap Stroke Icons project
Bootstrap stroke icons (BSS) is free of charge vector icon set created for famous [Twitter Bootstrap project](https://github.com/twbs/bootstrap). Glyphicon set is used by default and Bootstrap version 3.2 contains 200 icons. BSS uses stroke style and contains 205 fully compatible icons.

 
## Live example
Just save and open <a href="https://raw.githubusercontent.com/HighRobotics/Bootstrap-Stroke/master/preview.html" target="_blank">preview example</a> of the icons.
<br/>
<img src="https://fbcdn-sphotos-d-a.akamaihd.net/hphotos-ak-xap1/t31.0-8/12314675_983440951726447_2033016135636906280_o.png" alt="Bootstrap stroke icons" />

## How to enable

### Simple and fast solution with CDN 

We already prepared for you ready to use files.
* After Bootsrap installation replace file refererence from `bootstrap.min.css` to corrected one at [jsdelivr](`https://github.com/jsdelivr/jsdelivr/tree/master/files/bootstrap-stroke`) in the ```HEAD``` section of your page. To use Bootsrap 3.2.0 with Bootsrap-Stroke font just add reference to

```
<link href="https://cdn.jsdelivr.net/bootstrap-stroke/1.0.1/css/bss-bootstrap.3.2.0.min.css" rel="stylesheet" type="text/css">
```

This is it.

```bss-bootstrap.3.2.0.min.css``` is a based on ```bootstrap.min.css``` and differs only in font reference.

CDN provided by jsdelivr is a file hub with fast access from any world point.

### Advanced solution

For experienced users we provide ```.less``` files for private customization. After downloading Bootstrap source files make changes to the next files in less folder:

* Copy ```icons.less``` file from our source to Bootstrap less folder.

* Inside Bootstrap project edit ```bootstrap.less``` file and remove or comment line ```@import  "glyphicons.less";```, then include line ```@import "icons.less";```

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
Applying css file from jsdelivr CDN there will not be any changes in using icons. Same code is valid as in Bootsrap project, for example ```<span class="glyphicon glyphicon-star" />```.

In case of custom prefix like ```@icon-font-prefix: bss;``` use ```<span class="bss bss-star" />```. 

Read more about icon applying at [Bootrap Help](http://getbootstrap.com/components/).

## License
Code: [MIT](http://opensource.org/licenses/MIT),
fonts: [Creative Common 2.0](http://creativecommons.org/licenses/by/2.0/)


