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

### Block-Level Element
- HTML elements are usually either block-level elements or inline elements.
- A block-level element occupies the entire space of its parent element (container), thereby creating a block.
- Browsers typically display the block-level element with a new line both before and after the element. They have a rectangular structure. By default, these elements will span the entire width of its parent element, so it won't allow any other element to occupy the same horizontal space as itself.

<hr>
- block elements take the whole horizontal space of its parent element (container), stretching from left ot right and creating a block;
- browsers display a block-level element with a newline both before and after the element, like a stack of boxes;
- use blok-level elements to control the flow of the content on a document;
- div is one of the most used block-level elements;
- also, p, h1, ol, ul and li elements;
- by default we can place block-level elements next to each other;
- cna have set properties for the size (width and height)

### Inline Elements
- HTML elements that only occupy as much space as their content;
- allows for the side-by-side arrangement of elements;
- use to create a horizontal flow of page elements;
- span, a HTML links, button and input tag;

### Inline-Block Elements
- the same size as their content and we can place them next to each other and other inline elements;
- can have size properties;
- often used ot create grids;

### Flexbox
#### Parent Properties
- layout tool that allows to arrange things in rows or columns, reverse or rearrange the order of our items without needing to change the HTML code and it gives us control over whether we want out elements to wrap into multiple rows or columns;
- use flexbox parent properties to tell child elements how to behave;

#### Child Properties
- if we want specific children to behave differently, we can do it with child properties flex-basis, align-self and order;
- flex-grow: use to deal with any surplus space in the parent;
- flex-grow: if there is surplus space in the parent, flex-grow sets how much of this space an element may use compared with its siblings;
- flex-shrink: tells elements how much they should shrink when there is not enough space in the parent; use to affect the size of one or more child elements;
- flex-shrink can be seen as the reverse of flex-frow; these two properties can be set on the same element, but they will never be active at the same time, as flex-grow affects the element only if there is space left over in the parent, while flex-shrink affects the element only if there is not enough space in the parent;

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