# fixdivi-a11y-modules

Version 1.0.1
==========================================
* fix issue with icon hover color
* add support for full width button by adding "full" to Advanced > CSS Class

Version 1.0
==========================================
FD Button replaces standard Button Module
* Prevents screen readers from hearing icons
* Adds aria-label option
* Outputs true button markup if URL is blank or #
  
FD Icon replaces standard Icon module
* Prevents screen readers from hearing icons
* Adds aria-label option
* Can wrap icon in link or button markup

To reeduce confusion, we recommend that you turn off the standard button and icon modules once all existing instances have been converted to using the Fix Divi A11y versions.  How to turn off standard modules - https://divimundo.com/en/blog/how-to-hide-divi-modules-that-you-dont-use/

Directions
========================================
When adding an instance of the FD Button or FD Icon module to a page, use the fields under Content > Content to add your button/link text, url, aria-lable, id and whether or not it opens a new window.  Using Content > Link will not work. 
