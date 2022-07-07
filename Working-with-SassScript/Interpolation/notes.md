# Interpolation

Interpolation let's you work with variables that are defined by expressions.
Interpolation is essentially a code insertion. It allows us to interpolate SASS expressions into our code. We can use it to use a selector or property name, quoted or unquoted strings etc, as variables.
To interpolate an expression we need to wrap the expression using #{ }.

## Example

Below we have created two variables.

$b: "border";
$s: "side";

Below we are using interpolation.

a#{$s} .#{$s}-ad {
    box-sizing: #{$b};
    #{$b}-width: 2px;
}

Below is the outcome after using the interpolation.

aside .side-ad {
    box-sizing: border-box;
    border-width: 2px;
}