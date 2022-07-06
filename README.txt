css units **
display property
float:left|right; clear: left| right| both
css positions **
z-index and visibility
box shadow and text shadow
shorthand

CSS UNITS:
a) Absolute: px, cm, mm, in, pt
b) Relative:
em, rem, vh, vw, %
- vw means view port width and is the width of the entire window.
- vh is the viewport height which is the height of entire window.

DISPLAY PROPERTY:
- none
- inline
- block
- inline-block
- flex 
- grid

A div is a block level element and otherwise specified, it will display content as new line
display: inline-block comes in when we need both features of inline and thorse of block combined.

For the inline property, attributes like height will not apply to boxes but this will apply in the case of block.

flex and grid applied to the display attribute will help us achieve more

Display: none will not display nor will it hold space on the page while
visibility:hidden will show space but will not display the intended text or content.

Margin: auto will automatically allighn contents to the center.

CSS POSITION.
- The default position is static.
- The relative attribute has 4 properties, top, bottom, left and right.
- Absolute will always look for its nearest relative parent block or the parent containing it. If immediat parent is not relative, it will go one level higher.

If there is anything that needs alwasys to display, setting its position as static would be a good choice.

Position: sticky makes a box scroll but stick on the screan.
Most nav bars are set to a position of sticky. 
Fixed attribue will remain on a particular position of screen and is independent of scroll.


Z INDEX AND VISIBILITY

With visibility: hidden, any block can be hidden.
 
 Higher Z-index value will be above in case of any superposition. 
 Z-index values range from 1 through 4.


 BOX SHADOW AND TEXT SHADOW
 The following is a link to the css box shadow generator that helps in designing box shadows by click around to test different effects and properties.

 https://cssgenerator.org/box-shadow-css-generator.html