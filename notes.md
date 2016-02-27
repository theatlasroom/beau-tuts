# Notes

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
* [Melbourne ipsum](http://www.melbourneipsum.com.au/)
* [Markdown](https://daringfireball.net/projects/markdown/)

## Terminal
* cd - change directory
* ls - list files / folders

## Git
Central code sharing tool

* cloning a repo: git clone <repository-name>
* committing - saving a series of changes to some code

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

### Entities
used to render different symbols
&amps;: ampersand
&copy;: copyright logo
&nbsp;: non breaking space - give me space but dont start a new line

## Css
