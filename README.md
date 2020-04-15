# Notes



* text-align justify;   - spans pages
* text-align: right;  - align right
* text-align: left;  - align left
* text-align: center;   - centre text
* width:  -  set width
* height:     - set height
* strong- make bold
* em
* e- make italic/italicize
* s
* text-decoration: none;      - no decoration
* text-decoration: underline;   - give text an underline
* text-decoration: linethrough;   - make text strikethrough 
* br   add a line break
* hr  - add a line across page
* rbg values range from 0 - 255     r = red g = green  b = blue
* alpha values range from 0 - 1 (0 being transparent, 1 being opaque)
* rgba
* background-color:   - set background colour
* color:    - set text colour 
* font-family:   - set type of font
* font-size:  - set size of font
* padding:  - controls the amount of space between the element's content and its border
* margin: - controls the amount of space between an element's border and surrounding elements
* margin: -20px;   - akes the element grow bigger

* border: solid black 2px;
* box-shadow
* offset-x - how far to push the shadow horizontally from the element
* offset - y - how far to push the shadow vertically from the element
* blur-radius - 
* spread-readius
* color
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
* pseudo-class
* border-radius   - 50% = circle  5% = square
* text-transform: lowercase;    - make text lowercase
* text-transform: uppercase;   - make text uppercase
* text-transform: captialize;   - capitalize text
* line-height   - set line height 
* a:hover {          - use a pseudoclass - changes to red when mouse hovers over element
    color: red;
}
* block level elements - divs, headings, paragraphs
* inline elements - img, span
* position: relative; - specifies how the element should be moved relative to its current position
* position: absolute;  - lock an elmeent in place relative to its parent container
* position: fixed;  - locks an element in place (useful for navbar)
* float: right;
* float: left
* z-index: for overlapping elements (the most recently added element appears on top.
* The higher the z-index value, the higher the element is in the stack)
* margin: auto;    - centre an element
* RGB additive colour model
* primary + secondary colour = tertiary colour
* primary + primary colour = secondary colour
* hue - where a colour is on the colour spectrum
* saturation - amoutn of grey in colour
* lightness - amount of white or black in colour
* background: linear-gradient(90deg, pink, green) - 
* repeating-linear-gradient()
* colour stops
* background: url(link); - set an image from the web as background
* transform: scale() - change scale of element
* p:hover {
    transform: scale(2.1);
}
* transform: skewX(-32deg); - skew the element along the X-axis
* transform: skewY(-10deg); - skew the element along the Y-axis 

* Images should have alt text
* Elements with embedded landmark features
* main 
* header - workhouse tags
* navbarfooter
* header tags should have semantic meaning and relate to each other - not be picked
* merely for their size
* Only one h1 per page
* article - sectioning element - for standlone content
* section - sectioning element - for thematically linked content
* div - sectioning element - for unrelated linking
* figure + figcaption   figure(outer element) figcaption(inner element)
* label for forms
* wrap radio buttons in fieldset tag
* add legend tag to provide a description for the grouping

* href="#" - create a dead link
* a href="#contacts-header">Contacts</a> - create an interal link - jump to specified part of page

* CSS
* The most recently added class will override the others
* Ids override classes in CSS
* Inline styles override everything in CSS
* !important keyword overrides everything including CSS from libraries

* CSS Variables
* Create a variable like so:

* --face: pink;
