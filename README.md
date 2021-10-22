# Paddle_Temp_Files

```python
>from glob import glob
>import imghdr
>for i in glob('*'):
> print('FileName Extension: {}, imghdr return: {}'.format(i.split('.')[-1], imghdr.what(i)))

FileName Extension: png , imghdr return: png
FileName Extension: tiff, imghdr return: tiff
FileName Extension: ppm , imghdr return: ppm
FileName Extension: bmp , imghdr return: bmp
FileName Extension: jpeg, imghdr return: jpeg
FileName Extension: tif , imghdr return: tiff
FileName Extension: gif , imghdr return: gif
FileName Extension: pgm , imghdr return: pgm
FileName Extension: jpg , imghdr return: jpeg
FileName Extension: webp, imghdr return: webp

```
