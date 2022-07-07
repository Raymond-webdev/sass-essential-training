# @Mixin directive

A mixin is a chunk of a reusable css that we can just inject into any element that we want.
Mixins allow you to define styles that can be re-used throughout your stylesheet.
Mixins are defined using the @mixin at-rule, which is written @mixin <name> { ... } or @mixin name(<arguments...>) { ... }.
Mixins are included into the current context using the @include at-rule, which is written @include <name> or @include <name>(<arguments...>), with the name of the mixin being included.

## Example

@mixin list {
  margin: 0;
  padding: 0;
  list-style: none;
}

@mixin horizontal-list {
  @include list;

  li {
    display: inline-block;
    margin: {
      left: -2px;
      right: 2em;
    }
  }
}

nav ul {
  @include horizontal-list;
}