# travel-page

Practice about CSS & HTML deeply

## 3) Footer
* HTML tags
 - `<ul>`, `<li>`, `<img>`, `<a>`
  : input the images, Hiperlink in footer
 
* CSS Propertise
 -  `display: flex;`, `justify-content: center;`
    `width`, `height`
    : orginized the icons, re-size.

## 2) 2nd section of main (Highlight section)
What's Learn?

* HTML tags
  - `<strong></strong>`: font-weight: bold;
  - `<ul id="destinations">`, `<li class="destination">`, `<img src="/" alt="img">`: 3 images on Unordered list

* CSS Selector
  - `#destinations`: ID Selector (single)
  - `.destination img`: Class Selector (Multiple), Compound Selector

* CSS properties
  - `display: flex;`: Organized 3 images in row (default)
  - `box-shadow`, `border-radius` : Immprove appearance

* CSS functions
  - gradient 
    `background: linear-gradient(degree, color, color)`
    dgree : to lighting direction
    color : start color
    color : end color

* Flexbox properties related
  - `width: 100%;` : Flex container's width adjusts dynamically
  -`justify-content: center;` : center position of contents in flexbox 

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
  - `parents without margin(section)` + `child with margin(ul)`
    : Applied child margin over the parents margin.
    : fix to add the margin to the parents.

## 1) Header & 1st section of Main (hero section)
What's Learn?

* Understand HTML Skeleton (Header, Nav, Main, Footer)

* Flexbox
  - `flex-direction`: row, column;
  - `flex-wrap`: nowrap, wrap;
  - `flex-flow`: flex-direction flex-wrap;
  - `align-item`, `justify-content`

* Position & Layout
  - `position`: relative, absolute, fixed
  - `top`, `right`, `bottom`, `left`: px; (4 directions)

* Background Image
  - `background-image`, `background-position`, `background-size`, `box-sizing`
---------------------------lending pages starts-------------------------------