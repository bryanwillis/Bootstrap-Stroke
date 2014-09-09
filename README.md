## Welcome to Bootstrap Stroke Icons project
Bootstrap stroke icons (BSS) is free of charge vector icon set created for famous [Bootstrap project](https://github.com/twbs/bootstrap). Glyphicon set is used by default and Bootstrap version 3.2 contains 200 icons. BSS uses stroke style and contains 205 fully compatible icons.

 
## Live example
Just check this <a href="http://highrobotics.com/we-did-it/web/bootstrapstrokeicon.aspx" target="_blank">live example</a> of the icons.
<br/>
<a href="http://highrobotics.com/we-did-it/web/bootstrapstrokeicon.aspx" target="_blank">
<img src="http://www.highrobotics.com/media/images/bss_github.jpg" alt="Bootstrap stroke icons" /></a>

## How to use

### Glyphicon replacement
If your project already contains glyphicons then for compatibility name convention can be saved and glyphicons replaced. 
For example, using of _glyphicon glyphicon-plus_ does not require retyping it to _bss bss-plus_.

```
glyphicon_replacement/
+-- css/
¦   +-- bootstrap_stroke_replace_ref.css
¦   +-- bootstrap.min.css
+-- fonts/
    +-- bootstrap_stroke.eot
    +-- bootstrap_stroke.svg
    +-- bootstrap_stroke.ttf
    +-- bootstrap_stroke.woff
```

There are two solutions:
* Replace file `bootstrap.min.css with` with corrected one from `/glyphicon_replacement/css/bootstrap.min.css` and add link to it:
```
<link href="../css/bootstrap.min.css" rel="stylesheet" type="text/css">
```

or

* Copy `bootstrap_stroke_replace_ref.css` from `/glyphicon_replacement/css/` and include link after `bootstrap.min.css`:
```
<link href="../css/bootstrap_stroke_replace_ref.css" rel="stylesheet" type="text/css">
```
Solution with `bootstrap_stroke_replace_ref.css` has one problem with IE browser, font `glyphicon_halfings.eot` is downloaded in addition to `bootstrap-stroke.eot`.

### Solo Bootstrap Stroke icon set
In case of new icons using or additional using to another icons Bootstrap Stroke name convention should be used, e.g. _bss bss-plus_.

```
bss/
+-- css/
¦   +-- bootstrap_stroke.css
+-- fonts/
    +-- bootstrap_stroke.eot
    +-- bootstrap_stroke.svg
    +-- bootstrap_stroke.ttf
    +-- bootstrap_stroke.woff
```

Include link to css file in HEAD section of the html page after bootstrap.css linking:
```
<link href="../css/bootstrap_stroke.css" rel="stylesheet" type="text/css">
```
And then use icons with bootsstrap and bss name convention, e.g. _bss bss-plus_, _bss bss-share_, _bss bss-qrcode_.

## License
[MIT](http://opensource.org/licenses/MIT)

## Support or Contact
Having trouble with icons or want to say hi? Contact us via team@highrobotics.com.

