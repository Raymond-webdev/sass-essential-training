# Sass variables

Variables are a way to store information that you can re-use later. With Sass, you can store information in variables, like: strings. numbers. colors.
You assign a value to a name that begins with $, and then you can refer to that name instead of the value itself.

## Example

$base-color: #c6538c;
$border-dark: rgba($base-color, 0.88);

.alert {
  border: 1px solid $border-dark;
}