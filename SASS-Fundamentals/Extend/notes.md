# The @extend directive

The extend feature allows us to extend  or inherit CSS properties from another selector or from a mixin.
Sass’s @extend rule is written @extend <selector>, and it tells Sass that one selector should inherit the styles of another.

# Example

primary {
  border: 1px #f00;
  background-color: #fdd;

  &--list {
    @extend primary;
    border-width: 3px;
  }
}
