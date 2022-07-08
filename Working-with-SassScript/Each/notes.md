# @each directive

The directive Sass @each includes the value of each element in the list or map.

$var − It represents the name of the variable. @each rule sets $var to each item in the list and outputs the styles using the value of $var.

## Example
 
 $color: (
     youtube: #D16E8D,  
     facebook: #FFAC83,
     twitter: #3F78C9,
     tik-tok: #49C4A3,
      );

      @each $name, $color in $colors {
          .#{$name} {
              color: $color;
              }
          }
      }
