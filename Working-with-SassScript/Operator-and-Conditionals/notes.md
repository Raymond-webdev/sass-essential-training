#Source code

[Sass Math Functions](https://sass-lang.com/documentation/modules/math)

# Operators

Sass supports a handful of useful operators for working with different values. These include the standard mathematical operators like + and *, as well as operators for various other types:

== and != are used to check if two values are the same.
+, -, *, /, and % have their usual mathematical meaning for numbers, with special behaviors for units that matches the use of units in scientific math.
<, <=, >, and >= check whether two numbers are greater or less than one another.
and, or, and not have the usual boolean behavior. Sass considers every value “true” except for false and null.
+, -, and / can be used to concatenate strings.

# Conditions

Conditional statements allow us to control the flow of our scripts by evaluating conditions and executing code based on the result. The if statement will evaluate if a condition is true or false and execute its code block if the condition is true.

## Example

@if condition {
  // @if condition proves true
  // execute everything in the
  // code block
}
  //@else{
      // otherwise, execute this
  // else code block
  }


$dark-theme: true;

@if $dark-theme {
  color: #dedede;
  font-weight: 300;
  background-color: #191919;
}
@else {
  color: #191919;
  font-weight: 400;
  background-color: #fafafa;
}
