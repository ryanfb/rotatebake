# RotateBake

RotateBake is a Mac app for baking EXIF rotation into images. You know your
iPhone images that show up rotated wrong in Safari? Yeah, this fixes that.

[Download it now!](http://github.com/downloads/ryanfb/rotatebake/RotateBake.app.zip)

##SYNOPSIS

Drop images onto RotateBake and they will be rotated appropriately and have the EXIF rotation value stripped.

RotateBake has only been tested on OS X 10.6.

All RotateBake does is run the following command against each input image:

    jhead -autorot filename

##COPYRIGHT INFO

RotateBake bundles Intel-compiled versions of:

* [jhead](http://www.sentex.net/~mwandel/jhead/)
* [jpegtran](http://jpegclub.org/)
* [libjpeg](http://www.ijg.org/)

The cupcake icon is from [Graphicpeel](http://graphicpeel.com/icons).

RotateBake was created with [Platypus](http://www.sveinbjorn.org/platypus).

RotateBake "itself" is [WTFPL](http://sam.zoy.org/wtfpl/), provided you
abide by any additional restrictions of redistributed bundled components if
you also redistribute them.
