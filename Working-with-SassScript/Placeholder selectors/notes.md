# Placeholder Selectors

Placeholder is another special kind of selector. It is used when you are writing your own SASS library. Its work is very similar to mixin without arguments.

Placeholder selector starts with a % sign.

## Syntax:

%( name_of_selector ) { property: value; ... }

### Example

%button{
    padding: 10px 20px;
    border-radius: 15px;
    color: black;
}

.toolbar-button {
    @extend %button-format;
    background-color: lightpink;