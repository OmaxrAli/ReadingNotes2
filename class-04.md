#  Images

### Adding Images

# \<img>
this tag is a self closing tag used to add the image into the page 
you need to use an \<img>
element. This is an empty 
element (which means there is 
no closing tag). 

It must carry the following two components:


## src
This tells the browser where 
it can find the image file.
This will usually be a relative URL 
pointing to an image on your 
own site.

## alt
This provides a text description 
of the image which describes the 
image if you cannot see it.

## title
You can also use the title
attribute with the \<img> element 
to provide additional information 
about the image.
Most browsers 
will display the content of this 
attribute in a tootip when the 
user hovers over the image.

And we can declare the hight and the width og the images by using **hight** and **width** inside the tag

## height
This specifies the height of the 
image in pixels.
## width
This specifies the width of the 
image in pixels.

![Images in HTML](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSlj-JCS6Ht9I6BaWEOKbRk5d7dbrsMeBWG_w&usqp=CAU)


-----------------------

# Color

The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:

### rgb values
These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: **rgb(100,100,90)**
### hex codes
These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash \# 
sign. For example: **\#ee3e80**
### color names
There are 147 predefined color 
names that are recognized 
by browsers.

For example: 

**DarkCyan**

## background-color

body {
background-color: rgb(200,200,200);}

h1 {
background-color: DarkCyan;}

h2 {
background-color: #ee3e80;}

p {
background-color: white;}

![Colors in CSS](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXspslhXuzz4d4Q8bFJMFHHdZ10-EWbx5L1Zxhu_VM_5qknRGSZ2Yw57basfZbfJaA_d0&usqp=CAU)

-----------------------

# Text

## Size of Type
### font-size

The font-size property enables 
you to specify a size for the 
font. There are several ways to 
specify the size of a font.

The most common are:
### pixels
Pixels are commonly used 
because they allow web 
designers very precise control 
over how much space their text 
takes up.

The number of pixels is 
followed by the letters px.

### percentages
The default size of text in 
browsers is 16px.

So a size of 75% would be the equivalent of 
12px, and 200% would be 32px.

### ems
An em is equivalent to the width 
of a letter m


## Bold
### font-weight

The font-weight property 
allows you to create bold text. 

There are two values that this 
property commonly takes:

### normal
This causes text to appear at a 
normal weight.

### bold
This causes text to appear bold.

## rticle
### TEXT 280
If you want to create italic text, 
you can use the font-style
property. There are three values 
this property can take:

### normal
This causes text to appear in a 
normal style (as opposed to italic 
or oblique).

### italic
This causes text to appear italic.
oblique
This causes text to appear 
oblique.


## Alignment
### text-align

The text-align property allows 
you to control the alignment of 
text. The property can take one 
of four values:

### left
This indicates that the text 
should be left-aligned.

### right
This indicates that the text 
should be right-aligned.

### center
This allows you to center text.

### justify
This indicates that every line in 
a paragraph, except the last line, 
should be set to take up the full 
width of the containing box.

![Text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXR1e0mg8T5EWcv16oPOBjPhYijLBiT7GDyA&usqp=CAU)
