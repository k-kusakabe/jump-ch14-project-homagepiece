# The Jump Homage Piece Project

## Copy of Nowness.com (https://www.nowness.com/)

### Question

1. Burger menu cannot be scrolled properly.

- it can be scrolled under screen size =< 600px but the code does not look correct. Line 108 - 115 on "style.scss" was the original code but it did not allow the menu to scroll. Then, accidentially it worked when I wrongly put **"height: 100vw"** but it's not correct property (please see line 97 - 106 on style.scss).

- under screen size > 600px, I set "300px" for width and the menu stopped scrolling.
