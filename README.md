# Notes

**Formatting**

* **text-align justify;**   - spans pages
* **text-align: right;**  - align right
* **text-align: left;**  - align left
* **text-align: center**;   - centre text
* **width:**  -  set width
* **height:**     - set height
* **strong** - make bold
* **em** - italiticize
* **s** - add strikethrough to text
* **br**   add a line break
* **hr**  - add a line across page
* **block level elements** - divs, headings, paragraphs
* **inline elements** - img, span
* **text-decoration-thickness:** 3px;
* **text-emphasis:** filled red;
-webkit-text-emphasis: filled red;
* **text-shadow:** 0.5px 0.5px #726e6e;

<hr>

**CSS**

**Text**

*Import Google Fonts to make use of more interesting fonts*
by adding the following link within the head tag:
```html
<link href='https://fonts.googleapis.com/css?family=Sofia' rel='stylesheet'>
```

* **text-decoration: none;**      - no decoration
* **text-decoration: underline;**   - give text an underline
* **text-decoration: linethrough;**   - make text strikethrough 
* **color:    - set text colour** 
* **font-family:   - set type of font**
* **font-size:  - set size of font**
* **text-transform: lowercase;**    - make text lowercase
* **text-transform: uppercase**;   - make text uppercase
* **text-transform: captialize;**   - capitalize text

<hr>

**Colour**

* **rbg values range from 0 - 255**     r = red g = green  b = blue
* **alpha values range from 0 - 1** (0 being transparent, 1 being opaque)
* **rgba**
* **background-color:**   - set background colour
* **RGB additive colour model**
* **primary + secondary colour** = tertiary colour
* **primary + primary colour** = secondary colour
* **hue** - where a colour is on the colour spectrum
* **saturation** - amount of grey in colour
* **lightness** - amount of white or black in colour
* **background: linear-gradient(90deg, pink, green**) - 
* **repeating-linear-gradient()**
* **colour stops**

<hr>

**Spacing**

* **line-height:**   - set line height
* **padding:**  - controls the amount of space between the element's content and its border
* **margin:** - controls the amount of space between an element's border and surrounding elements
* **margin: -20px;**   - a negative value makes the element grow bigger
* **position: relative;** - specifies how the element should be moved relative to its current position
* **position: absolute;**  - lock an element in place relative to its parent container
* **position: fixed;**  - locks an element in place (useful for navbar)
* **float: right;**
* **float: left**
* **z-index** - for overlapping elements (the most recently added element appears on top.
* The higher the z-index value, the higher the element is in the stack)
* **margin: auto;**    - centre an element

<hr>

**Decoration**

* **border: solid black 2px;**
* **box-shadow**
* **offset-x** - how far to push the shadow horizontally from the element
* **offset - y** - how far to push the shadow vertically from the element
* **blur-radius** - 
* **spread-readius**

<hr>

**Animations**

* **animation-name:**   - give animation a name
* **animation-duration:**    - set length of animation
* **animation-iteration-count: infinite;**     - make animation happen continuously 
* **@keyframes**     - use keyframe rule to control scale and opacity at different points during the animation
* **animation-timing-function**
* **ease** - default - slow fast slow
* **ease-out** - fast slow
* **ease-in** - slow fast
* **linear** - constant
* **ease-in-out** - slow fast slow
* **cubic-bezier(n,n,n,n)**
* **transition-delay: 2s;**
* **transition- property: width;**

<hr>

**Accessibility**

* **Screen readers might:**
skip over landmark elements, skip to landmark elements, jump to the main context, get a page summary<br>
from the headings, only 'hear' the links on a page
* **Links need to be descriptive in order to provide meaning for users of screen readers**
* Images should have relevant **alt** text
* Elements with embedded landmark features
* **main** 
* **header** 
* **navbar**
* **footer** - put copyright information etc here
* header tags should have **semantic meaning** and relate to each other - not be picked merely for their size
* **Only one h1 per page**
* **article** - sectioning element - for standlone content
* **section** - sectioning element - for thematically linked content
* **div** - sectioning element - for unrelated linking
* **figure + figcaption**   figure(outer element) figcaption(inner element)
* **label** for forms
* **wrap** radio buttons in fieldset tag
* add **legend** tag to provide a description for the grouping
* audio **controls** attribute

<hr>

**Colour-blindness**

* Colour blindness can vary from reduced sensitivity to a certain wavelenth to an inability to 
see colour at all
* Most common form of colour blindness = reduced sensitivity to detect **shades of green**
* Use **high-contrast text** to alleviate colour-blindness-related issues
* WCAG recommends at least a contrast ratio of **4.5:1**
* Have sufficent contrast between **foreground and background colours**
* Colours shouldn't be to only way to convey important info - not detected by screen-readers

**Links**
```html
* <a href="url">Hello</a>  - adds a url link with the word Hello
```
* href="#" - create a dead link
```html
* a href="#contacts-header">Contacts</a>
```
 - create an interal link - jump to specified part of page

**CSS precedence**
* The **most recently added class** will override the others
* **Ids** override classes in CSS
* **Inline styles** override everything in CSS
* **!important keyword** overrides everything including CSS from libraries

<hr>

**CSS Variables**

* Create a variable like so:

* --face: pink;

<hr>

**Other**

* **centre an image** by adding the following to the image's class or id:
```html
display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
```

  
* border-radius   - 50% = circle  5% = square

```html
* a:hover {          - use a pseudoclass - changes to red when mouse hovers over element
    color: red;
}
```


* **background: url(link);** - set an image from the web as background
* **transform: scale()** - change scale of element

```html
* p:hover {
    transform: scale(2.1);
}
```

* transform: skewX(-32deg); - skew the element along the X-axis
* transform: skewY(-10deg); - skew the element along the Y-axis 

<hr>

**Responsive Web Design**

* With responsive web design, the layout changes based on the size and capabilities of the device. 
* Mobiles - content might collapse into a column
* Tablet - content might be in two columns, while content is much more spread out on a computer because the view port is much bigger 
 

* **Make an image responsive:**

```html
img {
  max-width: 100%;
  height: auto;
}
```

* **Media queries** - change the presentation of content based on different viewport sizes -
vary according to which device is being used.
* Can be applied to CSS styles

* This media query returns the paragraph when the device's width is no more than 800px

```html
@media (max-width: 800px) {
    p { 
      font-size: 10px;
    }
}
```


* An example of how to change a nav bar so that when viewed on a mobile phone, the navbar collapses into a column:

```html
@media screen and(max-width: 600px) {
  nav {
    flex-direction: column;
    align-items: center;
    background: pink;
  }
  a {
    color: grey;
  }
}
```

* An example of how to change a nav bar so that the layout of the nav bar changes when viewed on a device with a viewport that is smaller than that of a computer. e.g. a tablet:

```html
@media screen and(max-width: 700px) {
  nav {
    justify-content: center;
  }
}
```
**Typical Breakpoints**

* **Phones** - max-width 600px;
 **Large phones and portrait tablets** - min-wdith: 600px;
* **Landscape tablets** - min-width: 768px;
* **Laptop and desktop computers** - min-width: 922px;
* **Large laptops and desktop computers** - min-widthL 1200px;



* Retina images - to use a retina image - make the height and the width 50% of 
the original image's width and height

* **Make text responsive by using vw vh vmin vmax**

```html
body {
    width: 30vw;
}
```

sets the width of the body tag to 30% of the viewport's width

```html
h2 {
    width: 80vw;
}
```

sets the width of the h2 tag to 80% fo the viewport's width

```html
p {
    width: 75vmin;
}
```

sets the width of the paragraph as 75% of the viewport's smallest dimension

<hr>

**CSS Flexbox**

* Adding **display: flex;**   to an element turns it into a flex container
* The containing elements are flex-items
* We can set the flex-direction
* The default value for flex-direction is row
* **flex-direction: row;**   - makes elements sit side by side
* **flex-direction: column;**  - makes elements sit on top of each other (in a column)
* **flex-direction: row-reverse;** - reverses this <-
* *flex-direction: column-reverse;** - reverses this | up

**Parent and child elements**

* header {

}

* header is the **parent element**


* header .profile-name {

}

* **child element**

**There are two types of properties:**
 
* container properties - applies to the flex container
* flex item properties - applies to the individual flex items

**container properties:**
* align-items
* align-content
* flex-wrap
* flex-direction
* justify-content

**item properties:**
* order
* flex
* flex-grow
* flex-shrink
* align-self

**Container properties:**

**justify-content vs. align-items**

* **justify-content** and **align-items** do the **SAME THING**, but just along different axes

* **justify-content** - aligns items along the main axis
* for rows - the main axis is horizontal
* for columns - the main axis is vertical

* **justify-content: center;**
* **justify-content: flex-start;**
* **justify-content: flex-end;**
* **justify-content: space-between;**
* **justify-content: space-around;**
* **justify-content: space-evenly;**

* **align-items** - aligns items along the cross axis
* the default value for align-items is **stretch** 
* for **rows**- the cross axis is vertical
* for **columns** - the cross axis is horizontal

* **align-items: center;**

* the **default** for **align-items** is **stretch**
* for **rows** - vertically aligns
* for **columns** - horizonally aligns
* align-items: flex-start;
* for **rows** - elements pushed to the top of flex container
* for **columns** - elements pushed left
* align-items: flex-end;
* for **rows** - elements pushed to the bottom of the container
* for **columns** - elements pushed to the right
* align-items: stretch; - stretch items to fill the container
* for **rows** - stretch top to bottom
* for **columns** - stretch right to left
* align-items: baseline; - aligns items so that a line can be drawn through them, ene if the flex items are of different size

```html
.container {
  align-items: baseline;
}
```

```html
flex-direction: rows;
align-items: flex-end;
justify-content: center;
flex-wrap: wrap;
```



**align-content**

* **align-content** - defines how space is distributed BETWEEN  ROWS in the flex container
**ACROSS THE CROSS AXIS |**





* **flex-wrap** - allows you to split a flex item into rows and columns

* flex-wrap - tells CSS to wrap items
* the default is no wrap
* **no wrap** - doesn't wrap and content goes onto separate lines, growing to the width specified
* **wrap**
* for rows - wraps items from left to right
* for columns - wraps items from top to bottome
* **wrap-reverse**
* for rows - wrap items from right to left
* for columns - wrap items from bottom to top

* **flex-shrink** - shrinks if flex container is too small
the higher the number, the more it will shrink
* **flex-grow** - enlarges the item
the higher the number, the more it will grow
* **flex-basis** - sets the initial size of item
* flex shorthand property = allows you to specify flex-grow, flex-shrink and flex-basis in one way
**flex: 1 0 20px**
flex-grow = 1
flex-shrink = 0
flex-basis: 20px
order:  to specify the order items appear in the flex container

**Flex items properties:**

* **align-self** - overrides align-items - so you can single out an item and give it its own properties

```html

.flex-container {
  align-items: flex-end;
}

.flex-item {
  align-items: flex-start;
}
```

* the flex-item now follows the align-items: flex-start, overriding the flex-end

**order** - allows us to specify the order that flex items should be displayed

* can be used with responsive items - declare one order for one layout e.g computer layour
and a different order for a mobile layout

**flex** - defines how a flex item will grow or shrink to fit the available space in the flex container 
* it is shorthand for flex-grow, flex-shrink and flex-basis

**flex-basis** - specifies the ideal size of a flex item BEFORE it is place into a flex container
* flex-basis takes precedence i.e if a height and a flex-basis are defined for an element - flex-items takes priority


**flex-grow** - if items don't completely fill the flex container, flex-grow can be used to define how to divide up the extra space among the flex items 
* By default, flex-grow is 0

**flex-shrink**



<hr>


**CSS Grid**

* **display: grid;**   - creates a grid container on which you can use grid properties
* **grid-template-columns**  - creates columns in the grid container
* **grid-template-rows** - creates rows in the grid container 
* **column units** - fr % px
* **grid-column-gap** - creates gaps between columns
* **grid-row-gap**  - creates gaps between rows 
* **grid-gap** - shorthand for grid-column-gap and grid-row-gap
if one value only - creates gaps for all columns and rows
if two values - first value for rows, second value for columns 
***grid-column** - used on the grid items themselves. Can be used to specify how many
columns to consume
grid-column: 2 / 4; - consume the last two columns
* **grid-row** - used on the grid items themselves. Can be used to specify how msny
rows to consume
grid-row: 2 /4; - consume the last two rows


<hr>


**Bootstrap**

* Add Bootstrap to a project: 

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>
```

* To ensure proper rendering and touch zooming, add the following <meta> tag inside the <head> element: 

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

* Elements must enclosed in a container. 
Bootstrap 4 offers two classes:
* **.container**  provides a responsive fixed width container
* **.container-fluid** class provides a full width container, spanning the entire width of the viewport


* Make an image responsive by adding the **class "img-responsive"** to the image
* Centre an image by adding the **class "text-center"** to the image
* Create Bootstrap buttons - add the **btn and btn-default** classes to the button
* **btn-danger** - red - dangerous action
* **btn-success** - green - successful
* **btn-info** - light blue - optional actions
* **btn-primary** - darker blue - most important actions
* **BootStrap Grid** - made up of 12 columns

**Bootstrap 4 default settings:**
* **font-size:** 16px
* **line-height:**  1.5.
* **font-family:** "Helvetica Neue", Helvetica, Arial, sans-serif.

* All <p> elements have margin-top: 0 and margin-bottom: 1rem (16px)

**Bootstrap Headers**

* **2.5rem** 40px h1
* **2rem** 32px h2
* **1.75rem** 28px h3
* **1.5rem** 24px h4
* **1.25rem** 20px h5
* **1rem** 16px h6

**Bootstrap Displays**

* **Four classes:

* **.display-1**    biggest
* **.display-2**
* **.display-3**
* **.display-4**    smallest 

**<small>** tag - used to create smaller, lighter, secondary text in a heading 

**Bootstrap text colours**

**Classes to provide meaning through text:**
* **.text-muted** - grey
* **.text-primary**  - darker blue - important text
* **.text-success** - green
* **.text-info** - light blue - some information
* **.text-warning** - yellow   - warning 
* **.text-danger** - red - danger
* **.text-secondary** 
* **.text-white**
* **.text-dark**
* **.text-body** (default body color/often black) and .text-light:

**Bootstrap backgrounds**

* **.bg-primary**
* **.bg-success**
* **.bg-info**
* **.bg-warning**
* **.bg-danger**
* **.bg-secondary**
* **.bg-dark**
* **.bg-light**

**span** - allows you to put several elements on the same line 

**Add icons to pages by using Font Awesome**
**Add this link to the top of the html:**

```html
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
```


**Add a thumbs up icon to a button:**

```html
<button class="btn btn-black btn-primary"><i class="fas fa-thumbs-up"></i>Like</button>
```

**Add an info circle icon to a button:**

```html
<button class="btn btn-block btn-info"><i class="fas fa-info-circle"></i>Info</button>
```

**Add a bin icon to a button:**

```html
<button class="btn btn-block btn-danger"><i class="fas fa-trash"></i>Delete</button>
```

**Create a Bootstrap Well** to create visual depth:

```html
* **<div class="well></div>
```


# Sass - Syntactically Awesome Stylesheets

**Install Sass globally:**

```html
npm install -g sass
```

* **Sass** is a language extension of CSS.
* It is a preprocessor- it can extend the CSS language by taking code written in Sass**
**and convert it into basic CSS, allowing you to create variables, nest CSS rules into others,**
**import other Sass files, use mixins, and inheritance**



* There are two Sass syntaxes:

1. SCSS( Sassy CSS)
Files have the extension .scss

2. Sass 
Files have the extension .sass 

* **Sass Variables**

* **Declare Sass variables using $ :**

```html
$main-fonts: Arial, sans-serif;
$headings-color: green;
```

* **To use variables:**

h1 {
  font-family: $main-fonts;
  color: $headings-color;
}

* **Nest CSS using Sass:**

```html
nav {
  background-color: red;

  ul {
    list-style: none;

    li {
      display: inline-block;
    }
  }
}
```

* li is a child of ul and ul is a child of nav 

* **Sass Mixins**

**Mixins** are like functions for CSS - they are groups of CSS
declarations that can be reused throughout the style sheet

* **Declare** a mixin using the following:
**@mixin** followed by a custom name

```html
@mixin box-shadow
```

* **Call** a mixin using the following:
**@include directive e.g.

```html
div {
  @include box-shadow(0px, 0px, 4px, #fff);
}
```


**Sass partials**

* Partial Sass files can be created that contain bits of CSS that can be included in other Sass files. 
* Helps to modularize CSS and help keep things easier to maintain. 
* A partial is a Sass file named with a leading underscore  (just like with Rails). 
* The underscore indicates that the file is only a partial file and that it should not be generated into a CSS file. 
* Sass partials are used with the @use rule.
  

**Wireframes**

Wireframes are a useful way of planning the content and layout of a website before you start coding.
A wireframe is a drawing that shows the different elements of your page.

They help you plan out the design of each web page and make important decisions about how a page will be structured.

Wireframes also help you to decide how the user will interact with the page and move between the other pages on the website.



