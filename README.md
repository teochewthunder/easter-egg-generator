# Easter Egg Generator

This generator is really all about CSS shapes.
- Egg: A div with rounded corners
- Bands: Rectangular divs.
- Polka Dots: Divs with rounded corners.
- Stars: Spans with different border widths combined.
- Rainbow: Thick ellipses within a div with *overflow* set to *hidden*

Range inputs on the left control the CSS properties of the shapes whch are superimposed on the "egg". Properties that can be changed include:
- Color
- Width
- Height
- X and Y values
- Z-index

## Print Function
The CSS has been manipulated using media queries, to only show the egg and shapes when printed, hiding all the controls.

## Note
The CSS doesn't render very well in IE, though the JavaScript works well enough.
