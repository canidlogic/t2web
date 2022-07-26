# t2web

Virtual German T2 keyboard web app.

Everything is contained within the `t2.html` page, which is entirely client-side and may be run from the local file system without an HTTP server.  You may rename the HTML page anything you wish.

The HTML page assumes that the following webfonts are in the same directory as the HTML page:

- `NotoSans-Regular.woff`
- `DejaVuSerif.woff`

Noto Sans is used as the main display font, including for the symbols on the virtual keyboard.  Deja Vu Serif is used as the font in the input box.  You may substitute any fonts you want, though you will need to edit the CSS in `t2.html` if you change the fonts.

The web fonts should be in WOFF format.  You can use the `sfnt2woff` program to convert TTF fonts to WOFF for use with this web app.
