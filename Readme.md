# Test - Notes for HTML

when looking up information for html, css and javascript always write mdn at the end to get the website that has the most reliable information

## Headers:

- H1, H2, H3, H4, H5, H6
  - this are the different headers for html (left to right) largest to smallest

## Lists

- Li
  - list item, used inside of either a ul or a ol for each item
- Ul
  - unordered list, which is used to hold list items, this uses bullet points for each part
- Ol

  - ordered list, this is used to hold list items using numbers

## Anchor

- a
  - an anchor is a link thay we use to go to another webpage
  - needs more information compared to a title in order to acually allow the link to work
  - need to use attributes such as href (hyperlink reference
    - `<a href="http://google.com"> Google </a>`

## Image

    - img
        - a self closing tag <img />

## Form

- use with input and can get an input into a website
- input can also have many differnt types as well such as actual input and button, password date etc etc

## Div

BLOCK
have a width and height

- a div is like a box, so if you put elements inside of a div, they will be next to each other and then when you put them into seperate divs they will be on top of each other
- the other names listed below are also boxes and they are used to help understand the content

## header, main and footer

- this are essentially differnt kind of divs however they are seen as the same on the browser. one difference though is how the content it identified

## span

INLINE
inlines do not have a width or height

- is used for short text, they also allow elements next to each other unlike div

margin is the space from the border of the box to the outside

## Classes and ID's

- classes are a way to identify a group of elements within the code
- id's are unique identifiers for a specific element
- to move boxes anywhere I want need to talk to the father, not the children, need to make it a flexbox
  - such as talking to the body to move divs around
