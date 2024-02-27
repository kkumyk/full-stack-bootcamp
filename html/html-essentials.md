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

### Classes
- class is an HTML attribute that provides a common identifier to multiple elements; mostly used for styling allowing CSS and JS to select and access specific elements;
- elements with the same class will be treated as a group for collective styling;

### Lists

- the type of bullet-point used in the lists can be changed with CSS using list-style-type property;

### Semantic Web

#### \<section> element
- The \<section> element is used for a section of content when there isn't a more specific semantic element to represent it. Typically a \<section> will include a heading element, but this is not mandatory.
- use the \<section> element as a generic container for styling purposes only, in this case, we would use a \<div>;
- a section should logically appear in the flow of a document. If you were to write an index for the content of your page, a section would represent one of the things in the index of content. For example, a section should be a 'section' of a \<main>, \<footer> or \<header> etc, rather than just a division of space.

#### \<aside> element
- used for a portion of a document where its content is indirectly related to the document's main content;
- often used as a sidebar or call-out box;
- it does not, however, have any associated styling. The semantic meaning is just content that is only tangentially related to the web page content. It might be content that enhances the main content but is not critical to its understanding.

#### \<figure> element
- contains an image-based component
- the content of a figure element is referenced in the main flow of a document;
- the content of the figure should be self-contained;
- use to semantically organise the content of an image in the HTML document;
- by placing an image file into a figure element, you are telling the browser and search engines that the content of the figure could be seen on its own, separate form the rest of the content of the page, and still make sense;
- use where an image is not decorative but is referred to in an article.