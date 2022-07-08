# Parent selector

The parent selector, &, is a special selector within Sass that’s used in nested selectors to refer to the outer selector.
 It makes it possible to re-use the outer selector in more complex ways, like adding a pseudo-class or adding a selector before the parent.

 ## Example

 .parent {

  &.skin {
    background: pink;
  }
  &:hover{
      background-color: blue;
  }
}