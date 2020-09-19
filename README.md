# cody_refactoring_hw

Titled the website Horiseon so it would appear as such in the browser tab, letting you know the context within the tab.

Added reset.CSS.cdn link on line 7 to normalize the CSS to increase accessibility on all browsers. 

Since the style was the same for three different elements, I combined the elements under one class on lines 89, 94, and 99 to reduce code / file size. 

Line 94 is simply one h3 class because it is the only h3 tag in the html file.

Line 114 was condensed to one class due to the img attributes being the same for the three img elements. 

Got rid of the id class on lines 38 and 45 because they are styled the same on the css stylesheet.

Added alt image tags on lines 32, 39, 46, 56, 63, and 70

Since the hero image was inputted on the CSS style sheet, I added a title description for the image in place of an html alt tag. 