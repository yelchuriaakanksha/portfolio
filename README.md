# portfolio
Project Rubric
The page at minimum includes all of the following:
* 7 images
* Title text
* Regular (paragraph) text
* A logo.
* Semantic HTML
* HTML5 semantic tags such as header, footer, article, section etc. are used to add meaning to the code.
* No div or section tags are without a CSS class or id.

Custom Design:
* Customize images and text.
* Customize placement of the elements on the page (grid layout) with both HTML and CSS
* Customize CSS styles applied to paragraph and heading elements.
* Grid-Based Layout
* Page utilizes a grid-based layout with styles making use of the flexbox layout or a framework like Bootstrap, Foundation, etc. 
* Responsiveness
* Cross-Device Compatibility
All content is responsive and displays on all display sizes.

Testing Responsiveness:
* Test responsiveness with Chrome Developer Tools device emulation by right-clicking anywhere on page, selecting ‘Inspect Element’, clicking the rectangle to the left of the Elements tab, select Apple iPad or Google Nexus 5 from Device drop-down list, and click reload.
* All content is rendered on all three devices. No content should be hidden on mobile devices.
* Viewport meta Tag
* Viewport meta tag is included in HTML. (i.e. <meta name=”viewport” …)
* Responsive Images

If a CSS framework is used, classes provided by the CSS framework are used to make images responsive, otherwise media-queries are used to ensure responsiveness of images.

Separation of Concerns
Styles Separated From HTML

Portfolio completely separates structure (HTML) from design/style (CSS). There are no style attributes present in the body of the HTML document. 

File structure:
* Files are organized with a directory structure that separates files based on functionality. For example: css/ for stylesheets img/ for images js/ for JavaScript files

HTML Formatting rules:

* All code ( HTML element names, attributes, attribute values) is lowercase (except text/CDATA).
* Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).
* Code uses a new line for every block, list or table element and indent every such child element (it's acceptable to put all
elements in one line).
* When quoting attribute values, code uses double quotation marks.

HTML Style Rules:
* HTML documents use HTML5 <!doctype html>.
* Code passes HTML and CSS validators.
* Code does not use entity references unless necessary e.g. characters with special meaning in HTML (like < and &) as well as control or “invisible” characters (like no-break spaces).

CSS Formatting Rules:
* Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).
* Code indents all block content, that is rules within rules as well as declarations to reflect hierarchy and improve understanding.
* Code uses a semicolon after every declaration for consistency and extensibility reasons.
* Code always uses a space after a property name's colon, but no space between property and colon, for consistency reasons.
* Code always start a new line for each selector and declaration.
* Code always put a blank line between rules.
* Code uses double quotation marks for attribute selectors or property values.

CSS Style Rules:
* Code uses meaningful or generic ID and class names that are as short as possible but as long as necessary.
* Code uses element names in conjunction with IDs or classes.
* Code uses shorthand properties where possible.
* [Optional] Code separate words in ID and class names by a hyphen. *[Optional] Code avoids user agent detection as well as CSS "hacks"—try a different approach first.

 I have made the following choices in designing this website:

Use CSS without a framework such as Bootstrap. 
I used some CSS grid and some CSS flexbox. Both were kind of tricky to get to work the way I wanted. I think I like grid better of the two after completing this project.
