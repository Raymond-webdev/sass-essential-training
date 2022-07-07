# Source code

	[Sass Color Functions]](https://sass-lang.com/documentation/modules/color)

## Sass color functions

Sets one or more properties of a color to new values, increases or decreases one or more properties of $color by fixed amounts.
In order to add different color rules we need to add the @use "sass.color" rule.

## Example
 
 nav {
	 background-color: lighten( $color, 30)
	 color: transparentize($color, 1)
 }
