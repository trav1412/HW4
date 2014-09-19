HW4
===

1. There are maximum 255 combinations for each of the 3 colors in RGB
values.

def decreaseRed(picture):
for p in getPixels(picture):
value=getRed(p)
setRed(p,value*0.3)\

This swaps the red and blue values around:

def test6 (picture):
for p in getPixels(picture):
red=getRed(p)
green=getGreen(p)
blue=getBlue(p)
color=makeColor(blue,red,green)
setColor(p,color)


def pict():
file = 'C:\\Users\\tmart_000\\Desktop\\wantchekonbio.jpg'
pict = makePicture(file)
grayScale(pict)
show(pict)

def decreaseRed(picture):
for p in getPixels(picture):
value=getRed(p)
setRed(p,value*0.9)
