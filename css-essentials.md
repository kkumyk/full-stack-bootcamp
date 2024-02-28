# CSS Essentials

## CSS pseudo-classes

- a keyword added to a selector that specifies a specific state of the selected element or elements.
- let you apply a style to an element in relation to the content of the document, but also in relation to external factors like the history of the navigator.
- e.g.:visited can apply styles to links that are already in the browser history and therefore have been visited.
- can also target the status of the document content. E.g. :checked on a checkbox, or the position of the mouse with :hover. :focus represents an element that has received focus. It is generally triggered when the user clicks or taps on an element or selects it with the keyboard's Tab key. It helps highlight the current element that has been clicked.
- the colon before it tells the browser that it is a pseudo-class it should be looking for, and it is important not to put a space between the pseudo-class and the selector or the two will not be connected.
- can be applied to any css selector, be it type, class, id or attribute selectors.

## Units of measurement
- pixels (px)
- ems (em)
- rems (rem)
- percentage (%)
- viewport width (vw)
- viewport height (vh)

<hr>

- em and rem units are relative measurements.
- an em is relative to the font-size of the element ( 2em means two times the size of the current font). If no font-size is defined anywhere in the CSS, the em unit will be equal to the browser's default font-size for the document, which is usually 16px.
    - 1em = 16px
    - em size = pixel size/16

<hr>

- a rem - which stands for root em - is relative to font-size of the root element, meaning the <html> element.

- calculate rems by the following formula if the font-size of the root element ( <html> ) is 16px: rem = pixels / 16

- rems , unlike ems , are consistent. They do not depend on the values set by the parents of the current element, and so can be simpler to use when first working with relative units of measurement in CSS.

