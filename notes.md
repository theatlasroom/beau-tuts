# Notes
Just some notes for beau

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Notes](#notes)
	- [Resources](#resources)
	- [Terminal](#terminal)
	- [Git](#git)
	- [HTML](#html)
		- [Tags](#tags)
		- [General tags](#general-tags)
		- [Text tags](#text-tags)
		- [Nesting](#nesting)
		- [Attributes](#attributes)
		- [Entities](#entities)
	- [Css](#css)

<!-- /TOC -->

## Resources
* [MDN](https://developer.mozilla.org/en-US/) - Mozilla developer network
* [CSS - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
* [Melbourne ipsum](http://www.melbourneipsum.com.au/)
* [Markdown](https://daringfireball.net/projects/markdown/)
* [CSS Tricks](https://css-tricks.com/snippets/css/using-font-face/)
* [Fontawesome](http://fontawesome.io) - Free SVG icons
* [Font generator](http://www.fontsquirrel.com/tools/webfont-generator) - transform fonts into web friendly formats to embed in CSS
* [HTML5 boilerplate](https://html5boilerplate.com/) - good starter template for a html5 webpage
* [Bootstrap CSS](http://getbootstrap.com/) - Useful components for webpages ie grid layouts, common user interface elements, good default styles etc
* [Codeacademy](https://www.codecademy.com/learn/web) - Good free tutorials on html / css
* [Web safe fonts](https://developer.mozilla.org/en/docs/Web/CSS/font-family)

## Terminal
* cd - change directory
* ls - list files / folders
* mkdir - make a directory (folder)

## Git
Decentralized code collaboration tool

* cloning a repo: `git clone <repository-name>`
* adding: preparing files to be committed `git add <file name>`
* committing: saving a series of changes to some code `git commit -m 'This is a commit with a message'`
* pulling: pulling changes from the server / another person `git pull`
* pushing: sending your changes to a server / another person `git push`

## HTML
HTML - Hypertext markup language
* Markup - dictates to a client, how a document should be structured
* The clients html communicates with are web browser
* Doctype basically specifies to the browser how to render the html `<!doctype html>`
* HTML Tags are the most important part of html
* The 2 main sections of a html document are the:
  - head: this gives additional information to the browser about the document
  - body: this is where the content that is rendered on the page is stored

* Some semantic tags:
  - header - head of the rendered content
  - nav - page navigation
  - main - main page content
  - section - a section of a page
  - article - content that is self contained and would make sense out of the page context (ie a new article that can be reposted on different social media)
  - aside - side content

### Tags
[Full list of html elements from MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element)

### General tags
* div - division of content
* span - like a division but inline - make sense later

### Text tags
* h1 - level 1 heading. This is the most important heading
* h2 - level 2.....h6 - is the least important heading
* p - paragraph of text
* ul - unordered list container
* ol - ordered list container
* li - list item
* blockquote - quote, block of text
* a - anchor tag
* br - line break
* hr - horizontal line
* table
  - table: table element
  - thead: table head
  - tfoot: table foot
  - tbody: table body
  - th: table head column
  - tr: row
  - td: column
* form
  - form: specify the html form
  - fieldset: group of form elements
  - label: label for a form field
  - input: form field, comes in many types such as text, radio (radio button), checkbox, date, time, range, ....
* img - images
  - src: source of the image, can be a local reference or a web url
  - alt: alternate text


### Nesting
* there are some rules around how you can nest content
  - block level tags can be nested in block level tags
  - inline tags can be nested in block level tags
  - block level tags should not be nested in inline tags
* there are 2 types of tags:
  - block level tags: header, main, section, div, ul, blockquote
  - inline tags: li, a, p, h1, h2...

### Attributes
* Attributes define additional behaviour for a tag
`<a href="">` - the href attribute defines the destination for an anchor tag, it can be used for internal links using the `#` symbol
* id: unique identifier within a page
* class: an identifier for a group of elements

### Entities
used to render different symbols
&amps;: ampersand
&copy;: copyright logo
&nbsp;: non breaking space - give me space but dont start a new line

## Css
[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) - Cascading style sheets

* CSS rules have the form <element / selector / id / class > ->  { styles to be applied; }

* [Specifity](https://developer.mozilla.org/en/docs/Web/CSS/Specificity) - note: avoid using `!important` - its a bad habit to get into and can cause a lot of headaches down the track
* [box model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model)
* [Positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
* [Floating](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
* [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_flexbox_to_lay_out_web_applications) | [Good tutorial on flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Responsive web design](https://developer.mozilla.org/en-US/docs/Web/Guide/Responsive_design) | [Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
