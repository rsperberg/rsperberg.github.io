---
layout: post
title: Three Aspects of AngularJS Directives
post_author: Roger Sperberg
---
If you’re like me, your first encounter with AngularJS is a swirl of new terms and concepts, one of them — I hesitate to call it the most basic or most essential, but it does seem to be a common jumping-off point — being “directive.” What, you may ask yourself, is a directive?

The AngularJS [documentation](https://docs.angularjs.org/guide/compiler#directive "link to Angular Guide") says, “A directive is a behavior which should be triggered when specific HTML constructs are encountered during the compilation process.”

In other words, the guide goes on, "A directive is just a function which executes when the compiler encounters it in the DOM."

<a id="back1"></a>OK, let’s back up a little bit. [ [1](#note1) ] We are able to “attach behavior to any HTML element or attribute and even create new HTML elements or attributes with custom behavior. Angular calls these behavior extensions **directives**.”

Being able to extend HTML is no small wonder. When we investigate how to create a directive, the [guide](https://docs.angularjs.org/guide/directive/creating-directives "link to Angular Guide") says, “First let's talk about the API for registering directives.”

That is, before understanding this new term “directive” we need to learn what the heck it means to _register_ a directive.

Hm-m. Maybe there’s a simpler definition somewhere.

What’s a Directive?
--------------------

Joel Hooks at [egghead.io](https://egghead.io/articles/an-introduction-to-the-angularjs-directive-part-1 "link to Introduction to the AngularJS Directive Part I at egghead.io") usefully tells us that “Directives come in a couple of main flavors. The first is ‘behavior’ style directives. These directives are attached to HTML elements and provide some sort of augmented functionality.” (Unfortunately he doesn’t get to the part where he explains what the second flavor is. But this is a good start.)

The always informative [ng-newsletter](http://www.ng-newsletter.com/posts/directives.html "link to post on directives at ng-newsletter") explains, “Directives in AngularJS are, at their core, functions that get run when the DOM is compiled by the compiler.” It adds that we can “create new directives that we can encapsulate and simplify DOM manipulation. We can create directives that modify or even create totally new behavior in HTML.”

And in his [summary](http://tutorials.jenkov.com/angularjs/custom-directives.html "link to part 9 of Jenkov's 13-part AngularJS tutorial") of directives, Jakob Jenkov writes:

> “AngularJS directives are what controls the rendering of the HTML inside an AngularJS application. Examples of directives are the interpolation directive ( {{ }} ), the ng-repeat directive and ng-if directive.

> ”It is possible to implement your own directives too. This is what AngularJS refers to as ‘teaching HTML new tricks’.”

Other versions of these points may need to be disentangled. For instance, at [SitePoint](http://www.sitepoint.com/practical-guide-angularjs-directives/ "link to part I of A Practical Guide to AngularJS Directives at SitePoint") we are told “A directive is something that introduces new syntax. Directives are markers on a DOM element which attach a special behavior to it.”

<a id="back2"></a>In April 2013, Dan Wahlin recorded a [video](https://weblogs.asp.net/dwahlin/archive/2013/04/12/video-tutorial-angularjs-fundamentals-in-60-ish-minutes.aspx "link to AngularJS Fundamentals in 60-ish Minutes") [ [2](#note2) ] that nicely encapsulates the role of the directive.

> “A directive is really a way to teach HTML new tricks.

> “The web when it first came out was really just designed to display static pages. As we all know it’s become very dynamic and we’ve dealt with that pretty well. jQuery came out many years ago and it provided a way to do it. Even before then we could use raw, vanilla JavaScript.

> “Angular takes it up a whole notch and allows us to extend HTML very easily by simply adding attributes, elements or comments.”



<a id="note1"></a>[1] Literally back up a few paragraphs, to an [earlier point](https://docs.angularjs.org/guide/compiler#overview "link to Angular Guide") in the same document. [back to text](#back1)

<a id="note2"></a>[2] A transcript with many screen grabs of the video is available. It's described and linked to [here](http://weblogs.asp.net/dwahlin/angularjs-in-60-ish-minutes-the-ebook "link to post describing video transcript in PDF "). The [transcription](http://fastandfluid.com/publicdownloads/AngularJSIn60MinutesIsh_DanWahlin_May2013.pdf "direct link to video transcript in PDF of 'AngularJS Fundamentals in 60-ish Minutes' ") was created by <a href="http://twitter.com/FastAndFluid" target="_blank">Ian Smith</a>. [back to text](#back2)
