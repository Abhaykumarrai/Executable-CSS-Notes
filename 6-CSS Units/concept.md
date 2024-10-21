Note:- Every brouser have there default css.
     - The Default value of font size which is 16px which is equal to 100% which is equal to 





-Many CSS properties like width, margin, padding,  and font-size take a length, and CSS has many different ways to express length.

CSS units can be classified into two major categories:

1-Absolute
 - Absolute values are those value is fixed.
 - irrespective of any other factors like parent element or viewing window
 - the screen size won't affect the size of the element.
 - the mostly used absolute Unit is px (pixel) which is 1px = 1/96th of an inch
 - there are some other absolute units are available but rearly use tham 
    *point	1pt = 1/72th of an inch
    *pica	1pc = 1/6th of an inch
    *centimeter	2.54 cm = 1 inch
    *milimeter	10mm = 1cm

2-Relative - 

 - These units are relative to some other length property like the parent element's font size or the size of the viewport.
 - The most commonly used relative units are %, em, rem, vh, ch


em

  - 1em refers to the default size of the property
  - So precisely, 1em = 100%. and 1em = 16px
  - NOTE: Both % and em are inherited as they are RELATIVE TO THEIR PARENT! So, if we put parent font size as 2em then again we                   
    put child font size as 2em it would be added up to 4em (i.e 400% of the default value)! This might cause issues in the case of large CSS codes.

rem

  - rem stands for Root em
  - the browser will ignore all the adjustments made to the parent elements and will scale the HTML element, to which the property is applied,  based on the root/default value for that particular element.


CSS vh:
  - This stands for view height. If we want our element to have exactly the same height as your viewport/ view window then use 100vh to denote  that.

CSS vw:
  - vw stands for View Width. 100vw means 100% the width of the viewport/view window.
 
   