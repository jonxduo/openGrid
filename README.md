A grid css responsive really simple.


.:THE BOX WIDTH:..........

For widths greater than 600px, classes are:
.row: width 960px
.XL : width 100%
.L  : width 75%
.M  : width 50%
.S  : width 25%

.U3 : width 33.333%
.D3 : width 66.666%


For widths from 600 to 480px, classes are:
.row: width 100%
.XL : width 100%
.L  : width 50%
.M  : width 50%
.S  : width 50%

.U3 : width 33.333%
.D3 : width 66.666%


For widths less than 480px, classes are:
.row: width 100%
.XL : width 100%
.L  : width 100%
.M  : width 100%
.S  : width 100%

.U3 : width 100%
.D3 : width 100%


The suffix "-fix" fixing the width of the block irrespective of the width of the container.
in this case, the classes are:
.XL-fix : width 100%
.L-fix  : width 75%
.M -fix : width 50%
.S-fix  : width 25%

.U3-fix : width 33.333%
.D3-fix : width 66.666%




.:ORIENTATION CLASSES:..........

.left     : box is left-aligned
.right    : box is right-aligned
.center   : box is center-aligned

.t-left   : Text in the box left-aligned
.t-right  : Text in the box right-aligned
.t-center : Text in the box center-aligned




.:UTILITY CLASSESS:..........
.clearfix : clearfix :)




.:CLARIFICATIONS AND EXAMPLE:..........
 ______________
|.M____________|
 ______________
|.M____________|

 ______________   ______________
|.M.left_______| |.M.left_______|

 _______________________________
|.XL____________________________|
 ______________   ______________
|.M.left_______| |.M.left_______|
 __________   __________________
|.S.left___| |.L.left___________|
