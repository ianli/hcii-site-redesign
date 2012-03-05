---
layout: default
title: HCII Site Design Document
---

<div id="content-banner">
  <img src="img/banners/blueprint.jpg" />
</div>

Design Document
===============

This is the design document of the redesign of the [HCII web site](http://www.hcii.cmu.edu).

<hr class="space" />

Example Pages
-------------

* [Home Page](index.html)
* [About HCII Page](about.html)
* [Faculty Page](faculty.html)
* [Publications Page](publications.html)
* [Example Article Page](article.html)

<hr class="space" />

Code
----

The code for this redesign is available on GitHub at [https://github.com/ianli/hcii-site-redesign](https://github.com/ianli/hcii-site-redesign).

<hr class="space" />

Layout
------

The design of the layout emphasizes scanning from top to bottom instead of breaking content into separate pages or splitting navigation into separate menu bars. This property is evident in the flowing content of the example pages and the long list of links in the side navigation.

### Responsive

The layout is responsive. The elements of the layout scales and resizes to adapt to the screen resolution of the device. The readability of the site is maintained between different devices. To preview how this works, check this web site using a browser on the desktop and a mobile device. If you only have access to a desktop computer, try resizing the width of the browser.

<hr class="space" />

Page Elements
-------------

### Side Navigation

The side navigation is a good example of how vertical scanning is emphasized in the layout. The old design's top bar hides links behind drop-down menus. This is inefficient because the user has to look at each of the menus to find the link they want. Instead, the side navigation lists all the relevant pages on the site, which allows the user to easily scan from top to bottom.

The side navigation scrolls separately from the page content, so that users can navigate between pages more easily.

### Page Content

Long pages are not split into separate pages, but laid out completely in one page. This way the user can easily scroll through them, instead of waiting for a page load on another page. To help navigation in very long pages like the [Publications Page](publications.html), I added a simple quick search that filters the content dynamically based on the user's query.

### Banner

Each page has a banner with an image in it. The image is representative of the topic of the page, such as pictures of faculty on the [Faculty Page](faculty.html). This banner can also be used as a slideshow of several pictures. An example of this the banner in the [Home Page](index.html), which has a slideshow of pictures related to HCII.

### Top Bar

The top bar is fixed to the top, even when the users scrolls through the page. This is helpful in multiple ways:

- It's always clear that they are on the HCII web site.
- There is an easy way to return to the home page.
- The link 'Back to top' appears when the user scrolls. Clicking on this link is a fast way to return to the top of the page.

#### Font Choice

The font I used for the title and headings is [Helvetica Neue](http://en.wikipedia.org/wiki/Helvetica#Neue_Helvetica_.281983.29).
Helvetica Neue is humanist and ubiquitous, which reflects HCII's human-centered approach to technology that is permeating our lives.
It also complements Carnegie Mellon's wordmark font [Bauer Bodoni](http://en.wikipedia.org/wiki/Bodoni).

<hr class="space" />

Pages
-----

### Home Page

The home page should be a lively page that is updated constantly. It should make the user want to come back to the site for more updates. To accomplish this, the redesign has the following things on the home page:

- A banner that cycles through images about the latest news, events, and publications.
- Short descriptions about the latest HCII news, upcoming events, and recent publications are listed, so that users can easily scan through them.

### News

The old site separated news between HCII News and HCII in the Media. I think these pages should be merged into just one section for the following reasons:

1. The old site makes the user visit two separate pages to see all the latest news about HCII. This also meant that users had to subscribe to two RSS feeds.
2. These pages are not updated often enough to warrant their own pages. Putting them together would make the pages actively updated.
3. The old site had a column for HCII News and another for HCII in the Media. The two columns make it harder to scan and clutters the home page. Merged together, they are displayed as a list and is more easily scanned.


Colophon
--------

Code:
[HTML5](http://en.wikipedia.org/wiki/HTML5),
[CSS3](http://en.wikipedia.org/wiki/CSS3#CSS3),
[jQuery](http://jquery.com/),
[NiceScroll](http://code.google.com/p/jquery-nicescroll/)

Font:
[Helvetica Neue](http://en.wikipedia.org/wiki/Helvetica#Neue_Helvetica_.281983.29)

Layout:
[Twitter Bootstrap](http://twitter.github.com/bootstrap/)
