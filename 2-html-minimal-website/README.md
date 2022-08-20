# 2 HTML | a minimal webbsite

Pathname: 2-html-small-webbsite

The goal of the task is to create a small but, according to best practice, sufficient website with only html, where the architecture consists of a homepage and three subpages; index.html, products.html, about.html, contact.html

## General instructions
1. Structure the web pages with semantic elements like header, nav, section, article, aside

2. At least the following elements must be used:
    - h1, h2, p, a, ul or dl, table (with th, tr and td)

3. There should be a form element, including the following sub-elements
    - input (with submit, reset, text, checkbox /or radio values), select, textarea

4. At least one div element and span element

5. At least one relevant comment per page

Feel free to experiment with more awesome html element and attribute.

## Additional instructions

1. This is a group effort, and as such uses github (and Live Share where appropriate).

3. Your repo shoul must include, in addition to all other files
    - a README.md, where the website/project is described
    - a file called logbook.md, a written account of who did what
    - a .gitignore file

Please, do *not* use CSS or JavaScript for this task.

## Start-page

### ... from previous task

- [ ] Create a new file called index.html

- [ ] Create the following elements
  - doctype
  - html
  - head
  - body

- [ ] Place all necessary meta-tags inside the head, inkluding webbpage-name, description, etc

- [ ] Create the following content, inside correct element
  - a menu, with two links one called home and and one called contact
  - a header
  - a heading inside the header-element, with the text "Home"
  - a menu, with two links one called home and and one called contact
  - three longer texts (max 250 words, lorem ipsum), with headings
  - at least two images, where one is in a local folder and the other from a external page on Internet
  - a button with a link to another webpage on the Internet

### New addition to the start-page

- [ ] Add an internal video
  - download (or better: make one :)) a nice video from <https://www.pexels.com/sv-se/videos/>
  - use correct html syntax to add it to the startpage
  - the video should have the autoplay and muted attribute

- [ ] Add the pages about.html, products.html, and optional (see below for optional task) drawing.html to the menu, and make them work

- [ ] Add a footer with suitable texts

## Contact page

### ... from previous task

- [ ] Create a new file called contact.html

- [ ] Copy-and-paste everything from your index.html file, but change the text in the heading inside the header-element to "Contact us".

- [ ] Link the pages in the menu, so it is possible to navigate between the two web-pages

- [ ] Delete the images, and replace with one new

- [ ] In the contact-file, create a form with at least the following
  - set action to "mailto:firstname.lastname@mymail.eu"
  - a firstname label and an input
  - a lastname label and an input
  - a message label and a textarea
  - a submit and a reset button

### New addition to the contact-page

- [ ] Add some sort of a drop-down list to the form usting select with option

- [ ] Add a fieldset to the form

- [ ] Add some checkboxes or radiobuttons to the form

- [ ] Add an external video
  - Add a suitable video of your own choosing from Facebook using the iframe element

- [ ] Add the pages about.html, products.html, and optional (see below for optional task) drawing.html to the menu, and make them work

- [ ] Add a footer with suitable texts

## Products page

- [ ] Create a new file called products.html

- [ ] Create the following elements
  - doctype
  - html
  - head
  - body

- [ ] Place all necessary meta-tags inside the head, inkluding webbpage-name, description, etc
  - a header
  - a heading inside the header-element, with the text "Products"

- [ ] Create a menu, with all the four pages working (index.html, products.html, about.html, contact.html and optional (see below for optional task): drawing.html)

- [ ] Insert three pictures with productsr, choose photos from <https://www.pexels.com>. Each picture needs to be follow by information about the products name and price.

- [ ] Add a footer with suitable texts

## About page

- [ ] Create a new file called about.html

- [ ] Create the following elements
    - doctype
    - html
    - head
    - body

- [ ] Place all necessary meta-tags inside the head, inkluding webbpage-name, description, etc
    - a header
    - a heading inside the header-element, with the text "About us"

- [ ] Create a menu, with all the four pages working (index.html, products.html, about.html, contact.html and optional (see below for optional task): drawing.html)

- [ ] Insert three pictures of members from the border, choose photos from <https://www.pexels.com>, with names under each picture

- [ ] Add a nice quote with the correct element. If you need inspiration, use <https://www.goodreads.com/quotes>

- [ ] Add a footer with suitable texts

... but again, please feel free to add additional content.

## Optional: In-depth assignment - Painting using svg

> do only if you have time

- [ ] Create a new file called drawing.html

- [ ] Create the following elements
  - doctype
  - html
  - head
  - body

- [ ] Place all necessary meta-tags inside the head, inkluding webbpage-name, description, etc
  - a header
  - a heading inside the header-element, with the text "A suggested logo"

- [ ] Create a menu, with all the four other pages working (index, products, about, contact), and add drawing.html

- [ ] Make a nice logo and add it to the page, with the use of the element svg, its children and their attributes. <https://www.w3schools.com/html/html5_svg.asp>
