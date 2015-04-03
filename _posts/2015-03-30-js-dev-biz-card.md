---
layout: post
title: A JavaScript dev’s business card
hcolor: '#eeeeee'
post_author: Roger Sperberg
quote: Your card is an object, so treat it like one
image:
      url: /media/2015-03-30-js-dev-biz-card/cover.jpg
video: false
---
<p><img src="/media/2015-03-30-js-dev-biz-card/biz-card-back-500px-tall.png" width="331px" style="float:left; padding-right: 10px;" />As I’ve been applying for JavaScript dev jobs, I’ve been gradually tuning <a href="https://www.linkedin.com/in/rsperberg" title="link to rsperberg profile on LinkedIn">my LinkedIn</a> page and <a href="https://github.com/rsperberg/rsperberg.github.io/blob/master/assets/pdf/Sperberg_resume.pdf" title="link to my resume at GitHub">resume</a>, and last week I bent my business card toward contributing to the correct first impression — that I’m a developer the hiring manager wants to meet.</p>

To this end, I wanted to put some information on the business card that doesn’t normally reside there, things like the languages I know, GitHub repos and the JavaScript frameworks I’m familiar with.

Having stumbled across [JSON Resume](https://jsonresume.org/) recently, I realized I could easily represent this information as a JavaScript object without making the labeling seem obtrusive or out of place. Thus was born my JavaScript developer business card, whose details I share here for any developers who might want to use my work as a template for making their own similar cards.

To extend the conceit of _putting information about JavaScript in JavaScript notation_, I decided the card should use a programmer’s font, with syntax highlighting and a black background, the way such content appears in my text editor (the admittedly sublime [Sublime Text 3](http://www.sublimetext.com/ "link to Sublime Text site")). Although I admire and have contributed to [Source Code Pro](https://github.com/adobe-fonts/source-code-pro "link to Source Code Pro download page"), Paul D. Hunt’s superb monospaced font, for this card I make use of [Share Tech](http://www.google.com/fonts/specimen/Share+Tech "link to Google Fonts page for Share Tech"), a sans-serif font by Ralph du Carrois based on his design of the Share font family and closely connected to Share Tech Mono. Essentially Share Tech utilizes the Share Tech Mono glyphs but not monospacing; this means more characters fit on a line, and on my card only a single entry in the property-value pairs in the `info` object is split between two lines.

### Production choices
I use a color scheme that goes beyond my own (private) syntax-highlighting `NextUp.tmTheme`: `#ff5599` (light pink) for keyword1, `#2aff2a` (vivid lime green) for variable names, `#ff7f2a` (vivid orange) for punctuation, `#37c8ab` (moderate cyan) for brackets, `#e3dedb` (off-white) for properties, `#ffd42a` (vivid yellow) for strings and uri’s, and  `#5599ff` (light blue) for items in an array. (I’ve borrowed these color descriptions from [ColorHexa](colorhexa.com "link to colorhexa.com"), “a free color tool providing information about any color,” which I cannot praise enough.) Of course, no printed ink is ever truly “vivid,” so the physical business card is but a pale simulacrum of one’s text editor.

The proportions of this business card are not the traditional 2in-by-3.5in but instead the “slightly boxier” 55mm-by-84mm offered by [Moo](http://moo.com "link to moo.com"), the “award-winning print and design company specializing in premium business stationery and promotional materials.” Moo charges more than I want to pay, but everything about their work and products that I’ve seen is flat-out remarkable (which is why I indulge their puffed-up self description). I like the sturdy feel of Moo cards, so that’s where I now have my business cards printed.

### The source files
You can access the SVG files that I used as a [gist](https://gist.github.com/rsperberg/548202ff0de6c6b761e4). I created the design in [Inkscape](https://inkscape.org "link to inkscape.org") and generated the PDF’s that I sent to Moo from Inkscape. 

The SVG file for the back of the card is located at `https://raw.githubusercontent.com/rsperberg/rsperberg.github.io/master/assets/svg/js-dev-biz-card-back.svg` (the GitHub preview may or may not display the design accurately) and at this [gist](https://gist.github.com/rsperberg/548202ff0de6c6b761e4).

Here is a cleaned-up version of the SVG that Inkscape creates (I’ve removed the image preview, unused layers and redundant style information for readability):

{% gist 548202ff0de6c6b761e4 %}

The `<tspan>` elements specify where each line’s rendering is positioned; but if you did not wish to use Inkscape or some other vector-graphic editor to modify my file with your details, you can simply edit the text within the `<tspan>` tags to make your own card. (Theoretically. This modified file works beautifully with Inkscape but Chrome and Safari both render it differently than expected.)

Here is what the other side (the front) of this business card looks like. The SVG source file for the front side is located at `https://github.com/rsperberg/rsperberg.github.io/blob/master/assets/svg/js-dev-biz-card-front.svg` as well as part of the aforementioned [gist](https://gist.github.com/rsperberg/548202ff0de6c6b761e4).

<img src="/media/2015-03-30-js-dev-biz-card/biz-card-front-500px.png" width="500px" style="float:left; padding-right: 200px;" />

Obviously centering a title and catchline on a business card-sized template can be done in many programs. For consistency, black remains the background color. [Share Bold](http://www.google.com/fonts/specimen/Share) is used, since Share Tech lacks a bold weight.

<p>&nbsp; </p>

<small>last updated: March 31, 2015</small>

<small><img src="/media/2015-03-30-js-dev-biz-card/my-resume-word-cloud-240px.png" width="240px" style="float:left; padding-right: 10px;" />The main art on this page is a word cloud of Roger Sperberg’s resume that was created by <a href="http://tagxedo" title="link to Tagxedo site">Tagxedo</a>, using MKorsair, Franchise and Duality fonts, a custom rectangular shape dropping out the characters J and S, and the Wanderer color scheme (which I created and contributed to Tagxedo). If Wanderer doesn’t show up in Tagxedo, you can submit your own “theme” using the same colors: #087CF4 #D40A5A #FDC20F #03D518 #03B5D5.</small>

<p>&nbsp; </p>





