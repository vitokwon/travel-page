# travel-page

Practice about CSS & HTML deeply

## 2) Main (Card look)
* HTML tags
  - `<ul>`, `<li>` : creating the card layout
    `<img>`,`<div class="item-content">` : for Description 
    `<div class="actions">` : for links
      
* CSS properties
  - `Header {position:static}` : to separated from main
  - `.item-content {display: flex; flex-direction: column; justify-content: space-between;}`
    : content organized as top to bottom
  - `.actions {text-align: right;}`
  - `.actions a {text-decoration: none; padding: 6px; border-radius: 5px;}`
  - `.actions a:hover {}`
    : Decorating the `<a>` tag.

* CSS Grid properties
 - `display: grid;`
 - `grid-template-columns: 1fr 1fr;` : row, column
 - `gap: px;` : gap between grid

* CSS Grid Selectors
 - `li:first-of-type {}` : Select first Grid
 - `li:nth-of-type(3) {}` : Select Grid.No


## 1) Header & Footer
* Copied from index.html and revised samll things.
---------------------------Another Page(places.html) starts-------------------------------

---------------------------lending pages Ends-------------------------------
## 3) Footer
* HTML tags
 - `<ul>`, `<li>`, `<img>`, `<a>`
  : input the images, Hyperlinks in footer
 
* CSS Properties
 -  `display: flex;`, `justify-content: center;`
    `width`, `height`
    : organized the icons, re-size.

## 2) 2nd section of main (Highlight section)
What's Learn?

* HTML tags
  - `<strong></strong>`: font-weight: Bold;
  - `<ul id="destinations">`, `<li class="destination">`, `<img src="/" alt="img">`
    : 3 images in an unordered list

* CSS Selector
  - `#destinations`: ID Selector (single)
  - `.destination img`: Class Selector (Multiple), Compound Selector

* CSS properties
  - `display: flex;`: Organized 3 images in row (default)
  - `box-shadow`, `border-radius` : Improve appearance

* CSS functions
  - gradient 
    `background: linear-gradient(degree, color, color)`
    dgree : to lighting direction
    color : start color
    color : end color

* Flexbox properties related
  - `width: 100%;` : Flex container's width adjusts dynamically
  - `justify-content: center;` : centered content position in flexbox 

* Image Styling
  - `object-fit: fill;` (default)
    : Resized the image to fit the dimensions
  - `object-fit: contain;`
    : Resized the image to fit within the container while maintaining aspect ratio
  - `object-fit: cover;` (recommended)
    : Resized the image to fully cover the container while maintaining aspect ratio

* Text styling
  - `text-transform: uppercase;` : Uppered letters.
  - `text-align: center;` : center position of contents
  - `font-size: 40px;` : font size
  - `color: rgb(59, 65, 64);` : font color

* Margin Collapsing
  - `section without margin on parents` + `ul with margin on child`
    : Applied child margin over the parents margin.
    : fix to add the margin to the parents.

## 1) Header & 1st section of Main (hero section)
What's Learn?

* Understand HTML Skeleton (Header, Nav, Main, Footer)

* Flexbox
  - `flex-direction`: row, column;
  - `flex-wrap`: nowrap, wrap;
  - `flex-flow`: flex-direction flex-wrap;
  - `align-items`, `justify-content`

* Positioning and layout
  - `position`: relative, absolute, fixed
  - `top`, `right`, `bottom`, `left`: px; (4 directions)

* Background Image
  - `background-image`, `background-position`, `background-size`, `box-sizing`
---------------------------lending pages starts-------------------------------