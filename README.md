# workflow
My workflow building a website


1. Generate web fonts https://transfonter.org/
2. Add font preload in head tag e.g. ```<link rel="preload" href="fonts/Roboto.woff2" as="font" type="font/woff2" crossorigin />```
3. Load fonts with @font-face in CSS. local rule should be avoided because local fonts may have vertical metrics issue.
3. Generate favicon https://realfavicongenerator.net/
