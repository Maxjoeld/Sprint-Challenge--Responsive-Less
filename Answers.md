### What's a preprocessor
An extension of css that make it more powerful by cleaning up the code by making it more accessible and managable.
Preprocessors make it more efficient by reducing the amount of code and compiling the preprocessed code and converting it into css.

## What is the command in node package manager (npm) to install LESS globally on your computer?
npm install less -g


###Please provide an example of a mixin you have used in a project this week.
.bo-rad(@radius) {
  -webkit-border-radius: @radius;
     -moz-border-radius: @radius;
          border-radius: @radius;
}

.btn {
  bo-rad(100px);
}

###What is the difference between fixed layout, adaptive layout, and fluid layout?
Fixed layout is a website that does not respond to the browser width. Basically, not having any media queries that deal with different devices.
Liquid page layouts are based off percentages, allowing the width to respond to multiple devices unlike fixed layouts.
Adaptive layouts use media queries to respond to different widths of websites.

###Why do we need to use the CSS property max-width in a responsive website?
A lot of people don't maximize their browsers to the full width. Responsive layouts are usually built from mobile first and continues expanding 
