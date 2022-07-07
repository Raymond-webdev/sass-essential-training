# Sass Map Functions

In Sass, the map data type represents one or more key/value pairs. Tip: It is also possible to use the List functions from the previous page, with maps. Then the map will be treated as a list with two elements. Sass maps are immutable (they cannot change).
Maps aren't an automatically included moducle so you may have to use the @use rule to include them in your prject with the **@use "sass:map";**

## Example

$font-weights: ("regular": 400, "medium": 500, "bold": 700);