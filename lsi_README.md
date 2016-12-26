# lsi
List the images in a directory in thumbnail view (iTerm2)

#####Prerequisites:
[ImageMagick] (https://www.imagemagick.org/script/binary-releases.php)

Tested in iTerm2, osx 10.10.5.

#####Usage:
1. Navigate to the directory that contains the images you want to preview.
2. Issue the `lsi` command. Avaiable options are described below.


######Options:
1. -n
Change the number of images per row
`imagesDir$ lsi -n 6`
2. -d
Change the size of the thumbnails in pixels, they can only be squares.
`imagesDir$ lsi -d 200`
3. -h
Show help
