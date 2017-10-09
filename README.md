# toad.css
## toad.css is just my (very) tiny CSS grid system
###### Feel free to use / customize it / suggest some improvements

## Grid

The main container is 980px width. Want to change this width ? Just edit the @grid-width variable at the top of the LESS file

Here is the different combination with the grid system

Just add a toad-container class to your wrapper, and then add the t-1, t-2, t-3 … classes to the columns

Want to clear the float ? Add the toad-clear class to any element

Want to remove the gutters ? Just add the no-gutters class to the main container

You can also add a toad-full (100% width) or a toad-fullscreen (100vw width) class to any element

## Responsive

The grid system has 2 major breakpoints :

- 980px (the @grid-width variable)
- 736px (@breakpoint var)

You can edit them by changing the variables at the top of the LESS file, feel free to add more by the way

## Files

Here are the dev file (CSS), the LESS file and the prod file (min CSS)

## Website

This project is available online at [toadcss.tonyevariste.com](http://toadcss.tonyevariste.com/)
