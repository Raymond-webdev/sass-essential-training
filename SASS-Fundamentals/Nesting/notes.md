# Nesting style

Nesting allows you to write selectors that mimic the structure of your HTML. This allows you to use shortcuts to create your CSS. 

## Example

nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  li {
    display: inline-block;
  }
  a {
    display: block;
    padding: 6px 12px;
    text-decoration: none;
  }
}