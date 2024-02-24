# HTML Essentials
## \<div> and \<span>
- apply no direct meaning to their content
- can contain any content and context
- semantically neutral elements
- also known as structural elements
- used to represent divisions (div) or areas on a document’s layout
- we can also specify areas (spans) within these divisions
- the important thing to understand about \<div> is that by default, a \<div> will not share horizontal space with another element. So when you place two in your code one after the other, they will each spread the full width of their container. Therefore they will stack one on top of the other.

<hr>

### Block Level Element
- HTML elements are usually either block-level elements or inline elements.
- A block-level element occupies the entire space of its parent element (container), thereby creating a block.
- Browsers typically display the block-level element with a new line both before and after the element. They have a rectangular structure. By default, these elements will span the entire width of its parent element, so it won't allow any other element to occupy the same horizontal space as itself.

### The span Element
- generic inline container / inline container
- doesn't represent anything
- used to group elements for styling
- can be nested inside divs, but not vice versa