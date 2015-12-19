# tile-generator
Simple HTML tilegenerator with base64 output, uses canvas + JQuery.

This version exports textures of size 32x32 px, you can change it simply by altering patterns.png file. To do so, export image from patterns.svg with different resolution or using any file or use any image file, which contains square patterns, always one per row.

Principle:
Texture image with aplied foreground color is painted over it. As a result you can choose any foreground/background color and get small texture image as a result.. or use its base64 URL directly, like in demo.


online demo: http://www.textura.havala.sk/
