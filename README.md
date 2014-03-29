Deluminate, remixed
===================

An extension for Google Chrome (and Chromium) that inverts the luminance of
websites to make them easier on the eyes.

Remix
-----
This is a slight fork of Deluminate
https://github.com/abstiles/deluminate
https://chrome.google.com/webstore/detail/deluminate/iebboopaeangfpceklajfohhbpkkfiaa?hl=en-US

The vast majority of the work was done by https://github.com/abstiles. Please direct credit to him. Thanks Andrew!

Warning
-------
Because of the way this extension inverts the luminance of
rendered pages, it may cause noticeable slowdowns for some users. If this
happens, you may prefer another extension that uses custom CSS to set the
default background and text color of web pages.

Details
-------

Invert the brightness of the web without changing the colors! Useful as a night
mode to darken most bright web sites (like Google), or just for making the web
soothing black instead of glaring white. Similar to the "High Contrast"
extension by Google, but tries not to ruin images by blowing out the contrast or
changing the colors. It also offers a low-contrast mode and three strategies
for dealing with images, configurable on a per-domain basis!

### Invert Everything ###
In this mode, the luminance is inverted on everything, including all images.

### Keep Images Normal ###
In this mode, the plugin tries to avoid inverting the luminance on all images.
Useful for websites that make strange decisions about image types (e.g., using
PNGs for photos).

### Smart Invert Images ###
The default--this mode tries to intelligently choose whether images should be
inverted or not based on the following criteria:

 * Avoid inverting videos.
 * Since PNGs and GIFs are often used as stylistic elements and logos, they are
   typically safe to invert without looking strange. These images are detected
   by their file extensions.
 * Other images (in particular JPEGs) are typically photos that are often
   unrecognizable when inverted, so avoid inverting these.

Installation
------------

The latest release is always available on the Chrome Web Store. Search for
"Deluminate". The master branch always points to the latest Chrome Web Store
release code. Check out the dev branch if you want to see the latest unreleased
features, but only if you are willing to put up with more bugs.

License
-------

Copyright © 2014 Adam Wong adamwong246@gmail.com
This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the COPYING file for more details.
