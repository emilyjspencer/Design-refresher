# Notes

**Formatting**

* text-align justify;   - spans pages
* text-align: right;  - align right
* text-align: left;  - align left
* text-align: center;   - centre text
* width:  -  set width
* height:     - set height
* strong- make bold
* em - italiticize
* s - add strikethrough to text
* br   add a line break
* hr  - add a line across page
* block level elements - divs, headings, paragraphs
* inline elements - img, span

**CSS**

**Text**

*Import Google Fonts to make use of more interesting fonts*

* text-decoration: none;      - no decoration
* text-decoration: underline;   - give text an underline
* text-decoration: linethrough;   - make text strikethrough 
* color:    - set text colour 
* font-family:   - set type of font
* font-size:  - set size of font
* text-transform: lowercase;    - make text lowercase
* text-transform: uppercase;   - make text uppercase
* text-transform: captialize;   - capitalize text


**Colour**

* rbg values range from 0 - 255     r = red g = green  b = blue
* alpha values range from 0 - 1 (0 being transparent, 1 being opaque)
* rgba
* background-color:   - set background colour
* RGB additive colour model
* primary + secondary colour = tertiary colour
* primary + primary colour = secondary colour
* hue - where a colour is on the colour spectrum
* saturation - amount of grey in colour
* lightness - amount of white or black in colour
* background: linear-gradient(90deg, pink, green) - 
* repeating-linear-gradient()
* colour stops

**Spacing**

* line-height:   - set line height
* padding:  - controls the amount of space between the element's content and its border
* margin: - controls the amount of space between an element's border and surrounding elements
* margin: -20px;   - akes the element grow bigger
* position: relative; - specifies how the element should be moved relative to its current position
* position: absolute;  - lock an element in place relative to its parent container
* position: fixed;  - locks an element in place (useful for navbar)
* float: right;
* float: left
* z-index: for overlapping elements (the most recently added element appears on top.
* The higher the z-index value, the higher the element is in the stack)
* margin: auto;    - centre an element

**Decoration**

* border: solid black 2px;
* box-shadow
* offset-x - how far to push the shadow horizontally from the element
* offset - y - how far to push the shadow vertically from the element
* blur-radius - 
* spread-readius


**Animations**

* animation-name:   - give animation a name
* animation-duration:    - set length of animation
* animation-iteration-count: infinite;     - make animation happen continuously 
* @keyframes     - use keyframe rule to control scale and opacity at different points during the animation
* animation-timing-function
* ease - default - slow fast slow
* ease-out - fast slow
* ease-in - slow fast
* linear - constant
* ease-in-out - slow fast slow
* cubic-bezier(n,n,n,n)
* transition-delay: 2s;
* transition- property: width;



**Accessibility**

* Screen readers might:
skip over landmark elements, skip to landmark elements, jump to the main context, get a page summary<br>
from the headings, only 'hear' the links on a page
* Links need to be descriptive in order to provide meaning for users of screen readers
* Images should have relevant alt text
* Elements with embedded landmark features
* main 
* header - workhouse tags
* navbar
* footer - put copyright information etc here
* header tags should have semantic meaning and relate to each other - not be picked merely for their size
* Only one h1 per page
* article - sectioning element - for standlone content
* section - sectioning element - for thematically linked content
* div - sectioning element - for unrelated linking
* figure + figcaption   figure(outer element) figcaption(inner element)
* label for forms
* wrap radio buttons in fieldset tag
* add legend tag to provide a description for the grouping

**Colour-blindness**

* Colour blindness can vary from reduced sensitivity to a certain wavelenth to an inability to 
see colour at all
* Most common form of colour blindness = reduced sensitivity to detect shades of green
* Use high-contrast text to alleviate colour-blindness-related issues
* WCAG recommends at least a contrast ratio of 4.5:1
* Have suffificent contrast between foreground and background colours
* Colours shouldn't be to only way to convey important info - not detected by screen-readers

**Links**
* <a href="url">Hello</a>  - adds a url link with the word Hello
* href="#" - create a dead link
* a href="#contacts-header">Contacts</a> - create an interal link - jump to specified part of page

**CSS precedence**
* The most recently added class will override the others
* Ids override classes in CSS
* Inline styles override everything in CSS
* !important keyword overrides everything including CSS from libraries

**CSS Variables**

* Create a variable like so:

* --face: pink;

**Other**

* border-radius   - 50% = circle  5% = square

* a:hover {          - use a pseudoclass - changes to red when mouse hovers over element
    color: red;
}



* background: url(link); - set an image from the web as background
* transform: scale() - change scale of element
* p:hover {
    transform: scale(2.1);
}
* transform: skewX(-32deg); - skew the element along the X-axis
* transform: skewY(-10deg); - skew the element along the Y-axis 



**Responsive Web Design**

**CSS Flexbox**


**CSS Grid**


