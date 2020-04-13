Styling with Scss

What is a Scss mixin?
- the @mixin directive allows you to compile duplicated CSS into a single-change value.  

Will Scss render in the browser? Why or why not?
- No. Browsers use uncompiled CSS

How do you assign a variable in Scss and give me a use case
- use the '$' symbol. Example: $mainColor: red;

What is Variable Scope?
- It means the Scss variable can only be applied at the level where it's nested.

What is Pseudo Selector Nesting? 

Why would you use default variables in Scss?
- To ensure the value is set to a default even when no input is added/applied.

What is the purpose of Scss?
- to increase the speed/efficiency/simplicity of appliying CSS values.

What are some differences between Sass and Scss? 

- Sass follows strict indentation, Scss has no strict indentation.
- Sass has more developer community and support than Scss
- Sass has a loose syntax with white space and no semicolons. Braces and semicolons are mandatory for scss

What is the Scss @import Directive used for?
- Used for importing other files/code into your page.

What is the porpose of the @content Directive in Scss?

CSS GRID BASICS

What is the main purpose of CSS Grid?
- To assist in displaying elements on a page using columns and rows

How do you start using CSS Grid with css?
- Display: grid;

What is grid gap used for?
- To specify the thickness of the border-line area surrounding each grid cell.

What are grid columns?
- The vertical lines of the grid area.

What is the CSS grid repeat function?
- Can be used to repeat specifically measured columns within the function to fill up the provided grid area.

What does 1fr represent?
- 1 Fractional Unit

What are grid rows?
- The Horizontal lines in the grid area.

What is the purpose of Justify Items?
- Used to align grid items along the row axis

What is the purpose of Align Items?
- Used to align grid items along the column axis

What does grid-column-start do?
- Specifies where an item begins to appear along the vertical axis

Flexing with Flexbox

What is the main purpose of Flex Box?
- To provide an efficient way to layout items in a container even when their size is unknown.

How do you start using Flex Box with css?
- Display: flex;

Which should you use? Flex Box or CSS Grid?
- Depends on the desired layout, but they can both be used to together.

After declaring display flex, which elements are going to be affected by your flex styles?
- The item's children (Items nested inside the 'Flex container')

What is the purpose of Flex Direction?
- To specify the direction the flex will be utilized (row or column)

What is the purpose of Justify Content?
- To specify the justification of the content within the flex container wether it be left(flex-start), right(flex-end), center, etc.

What is the purpose of Flex Grow?
- The rate at which an item will expand when the browser page is enlarged. Example: an item with a flex-grow value of 4 will expand four times faster than an item with a flex-grow value of 1.

What is the purpose of Flex Shrink?
- Similar to flex-grow but in reverse. Also needs a default size set (Flex-basis).

What is the purpose of Flex Wrap?
- To allow items to be neatly rearranged on the page when the browser window is adjusted. 

What is the purpose of Align Items?
- The align-items property defines the default behavior for how items are laid out along the cross axis (perpendicular to the main axis).