# Week 16A CSS Calculator
Repository for the CSS Calculator task.

I didn't make this project by myself, it is based on a tutorial linked below!

# Description
- CSS3 box shadows are used to create the 3D effect and transitions are used for the smooth press effect. Basic regex is used for 
validations and text replacements.

- For every button(number or operator) pressed, the value is appended to an equation string displayed on the calculator screen which is 
later used in the JS eval function to generate the output.

# Author's tutorial
- http://thecodeplayer.com/walkthrough/javascript-css3-calculator

# Additional info
I came across a problem that the calculator is not working despite the CSS design appearing fine.
This is caused by a missing jquery import. I included that particular file (jquery.min.js) in the project and imported it inside the index.html so it now works fine.
