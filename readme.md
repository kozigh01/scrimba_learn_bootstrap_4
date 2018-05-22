# Learn Bootstrap 4

## Course Info
Course: [Learn Bootstrap 4](https://scrimba.com/g/gbootstrap4)  
Author: Neil Rowe  
Provider: [scrimba](https://scrimba.com)  

## Course sections

### Responsive Grid System
* See 02_responsive-grid-system.html
* Bootstrap uses a 12 column grid system
* "Basic Column": column class divides the space equally between siblings
* "Set Sizes": use col-<x> class where <x> is the number of columns to allocate:
    * To fill width, columns must add to 12 for all siblings
    * If add to < 12, then will not fill row
    * If add to > 12, then some siblings will wrap to next line
* "Breakpoints": use col-<bp>, where <bp> is  extra small (just col), col-smp, col-md-, col-lg-, col-xl- 
    * Each bp is defined as the width where horizontal layout switches to verticle layout
    * see [bootstrap 'Grid System' docs](https://getbootstrap.com/docs/4.0/layout/grid/) for breakpoint widths
* "Set Sizes and Breakpoints": use col-<bp>-<x> to combine set sizes and breakpoints
* "No Gutters": adding no-gutters class removes padding inside columns
* "Offsetting Columns": adding an offset class moves a column over leaving a gap defined by the offset
* "Multiple Breakpoints": can add classes for multiple breapoints to have different layouts for different widths.  For example, want 2x2 grid between sm and md breakpoints, then 4-1 bigger than md

### Responsive Navbar
* see 03_responsive-navbar.htm
* navbar-light bg-light: set the overall nav bar color and background color
