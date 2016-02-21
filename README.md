# SVG test

Dear Github, please, set proper Content-Type and Content-Encoding then serving `.svg` and `.svgz` files.

## This doesn't work (but viewing as file works fine)
Content-Type: image/svg+xml
![SVG test](footer__copyright-logo_lang_ru.svg)

## This doesn't work (and viewing as file doesn't works too) 
Content-Type: image/svg+xml
Content-Encoding: gzip
![SVGZ test](footer__copyright-logo_lang_ru.svgz)
