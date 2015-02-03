---
layout: post
title: Eric Elliott’s essential JavaScript links or The way of the parrot, not
post_author: Roger Sperberg
quote: How does the novice learner distinguish difficult-to-grasp concepts from inept explanations written by parrots?
image:
      url: /media/2015-02-01-essential-js-links/cover.jpg
video: false
---
There is a ton of learning material about JavaScript on the web,  and as a developer looking to achieve “mastery” in JavaScript, AngularJS and famo.us, I have buried myself under the weight of it, not always able to discern difficult-to-grasp concepts from inept explanations written by, well, parrots. (Who are these parrots? Facile developers who quickly picked up some framework — _I’m looking at you, Angular_ — and who by way of explanation merely mouth the words others taught them without clarifying _why_ something different is different or whether that difference is significant or not).

Of course, my catholic intake of everything Angulared and JavaScripty has led me to lists curated by my elders, the first of which I present here. By “present” I actually mean _re-_present because this list of essential JavaScript links from Eric Elliott was posted as a GitHub gist by Elliott and is not only [still there](https://gist.github.com/ericelliott/d576f72441fc1b27dace title="link to Eric Elliott gist"), it regularly acquires fresh items.

I lack the credentials to dispute Elliott’s choices or to supplement them, but I hope my _re-_presentation is valuable by the addition of my own obsessive labors providing visuals of each link presented and a short summary or description that the site itself provides.

Elliott’s gist list is quickly scanned, despite its length (134 items at the end of January 2015). My bulky rendition is not. Rather the goal is to enable a quicker decision as to which resources to explore first by providing some sense of what each one is about. &nbsp; *—Roger Sperberg*

<p>&nbsp; </p>

## Required Reading (Online resources)

### [Learn JavaScript Essentials (for all skill levels)](https://medium.com/javascript-scene/learn-javascript-b631a4af11f2 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/learn-javascript.png" width="480px" %}

One clear path to JavaScript mastery. <br />
_By Eric Elliot. Published at medium.com on August 2, 2014_

### [JavaScript Training Sucks](https://medium.com/javascript-scene/javascript-training-sucks-284b53666245 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/javascript-training-sucks.png" width="480px" %}

99 out of 100 JS developers lack the skills they need to fill hundreds of thousands of jobs. We can change that. <br />
_By Eric Elliot. Published at medium.com on December 29, 2014_


### [The Two Pillars of JavaScript Part 1: Prototypal OO](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/the-two-pillars-of-javascript-pt-1.png" width="480px" %}

“You never need classes in JavaScript, and I have never seen a situation where class is a better approach than the alternatives.” <br />
_By Eric Elliot. Published at medium.com on October 21, 2014_


### [The Two Pillars of JavaScript Part 2: Functional Programming](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/the-two-pillars-of-javascript-pt-2.png" width="480px" %}

“Closures are a mechanism for containing state. In JavaScript, a closure is created whenever a function accesses a variable defined outside the immediate function scope. It’s easy to create closures: Simply define a function inside another function, and expose the inner function, either by returning it, or passing it into another function. The variables used by the inner function will be available to it, even after the outer function has finished running.” <br />
_By Eric Elliot. Published at medium.com on December 12, 2014_

### [JavaScript Objects](http://davidwalsh.name/javascript-objects "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/javascript-objects.png" %}

An excellent explanation of inheritance in JavaScript. “JavaScript has been plagued since the beginning with misunderstanding and awkwardness around its ‘prototypal inheritance’ system, mostly due to the fact that ‘inheritance’ isn't how JS works at all, and trying to do that only leads to gotchas and confusions that we have to pave over with user-land helper libs. Instead, embracing that JS has ‘behavior delegation’ (merely delegation links between objects) fits naturally with how JS syntax works, which creates more sensible code without the need of helpers.” <br />
_By Kyle Simpson. Published at davidwalsh.com on April 22, 2013_


### [Isomorphic JavaScript](http://isomorphic.net/ "link to isomorphic.net")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/isomorphic.png" %}

“Isomorphic JavaScript apps are JavaScript applications that can run both client-side and server-side.
The backend and frontend share the same code.”


### [JavaScript Application Architecture on the Road to 2015](https://medium.com/@addyosmani/javascript-application-architecture-on-the-road-to-2015-d8125811101b "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/javascript-application-architecture.png" %}

“On an architectural level, the way we craft large-scale applications in JavaScript has changed in at least one fundamental way in the last few years. Once you remove the minutia of machinery bringing forth unidirectional data-binding, immutable data-structures and virtual-DOM (all of which are interesting problem spaces) the one key concept that many devs seem to have organically converged on is composition. Composition is incredibly powerful, allowing us to stitch together reusable pieces of functionality to ‘compose’ a larger application....

”Note: earlier players in the JS framework game (Dojo, YUI, ExtJS) touted composition strongly and it’s been around forever but it’s taken us a while for most people to grok the true power of this model as broadly on the front-end.” <br />
_By Addy Osmani. Published at medium.com on December 15, 2014_


### [Reactive MVC and the Virtual DOM](http://futurice.com/blog/reactive-mvc-and-the-virtual-dom "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/reactive-mvc-and-the-virtual-dom.png" %}

Great read, even if you're not a React user. “The new great idea in React is Virtual DOM Rendering. The gist is to frequently re-render a complete and lightweight representation of the DOM, then apply a difference filter to detect the minimum changes that need to be made to the DOM. A similar technique has existed in game development long before React: re-render the game screen in every game loop, but only update the minimum portion of the screen which changed compared to the previously rendered screen.” <br />
_By Andre Medeiros. Published at Futurice on November 2, 2014_


### [The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754 title="link to gist")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/introrx.png" %}

“Reactive programming is programming with asynchronous data streams.

“In a way, this isn’t anything new. Event buses or your typical click events are really an asynchronous event stream, on which you can observe and do some side effects. Reactive is that idea on steroids. You are able to create data streams of anything, not just from click and hover events. Streams are cheap and ubiquitous, anything can be a stream: variables, user inputs, properties, caches, data structures, etc. For example, imagine your Twitter feed would be a data stream in the same fashion that click events are. You can listen to that stream and react accordingly.” <br />
_By André Staltz. &nbsp;<img src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/angularjs/list-of-angular-resources/resources-white/star-32.png" width="20px" />star:&nbsp;3,101 &nbsp;<img src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/angularjs/list-of-angular-resources/resources-white/repo-forked-24.png" width="16px" />fork:&nbsp;282_


### [A General Theory of Reactivity](https://github.com/kriskowal/gtor "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/general-theory-of-reactivity.png" %}

What is all this talk about reactive? Functional? Promises? This is the beginning of a reactive programming bible. “In the context of a computer program, reactivity is the process of receiving external stimuli and propagating events. This is a rather broad definition that covers a wide variety of topics. The term is usually reserved for systems that respond in turns to sensors, schedules, and above all, problems that exist between the chair and keyboard....

“[V]arious minds in the field of reactivity have been converging on a model that unifies at least promises and observables.” <br />
_By Kris Kowal. First posted at github on August 9, 2014. 5 contributors &nbsp;<img src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/angularjs/list-of-angular-resources/resources-white/star-32.png" width="20px" />star:&nbsp;401 &nbsp;<img src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/angularjs/list-of-angular-resources/resources-white/repo-forked-24.png" width="16px" />fork:&nbsp;12_


### [ES6 Generators](http://davidwalsh.name/es6-generators "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/es6-generators.png" %}

A series of blog postson ES6 generators: “Whether you realized it or not, you've always been able to assume something fairly fundamental about your functions: once the function starts running, it will always run to completion before any other JS code can run....

“With ES6 generators, we have a different kind of function, which may be paused in the middle, one or many times, and resumed later, allowing other code to run during these paused periods.” <br />
_By Kyle Simpson. Published at davidwalsh.com, July – August 2014_


### [Typed JavaScript](http://www.2ality.com/2014/10/typed-javascript.html "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/typed-javascript.png" %}

Excellent post about the state of typed JavaScript via Microsoft’s TypeScript, Facebook’s Flow and Google’s AtScript. <br />
_By Axel Rauschmayer. Published at 2ality  and updated on November 18, 2014_


### [Taming the Asynchronous Beast with CSP in JavaScript](http://jlongster.com/Taming-the-Asynchronous-Beast-with-CSP-in-JavaScript "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/Taming-the-Asynchronous-Beast.png" %}

“Every piece of software deals with complex control flow mechanisms like callbacks, promises, events, and streams. Some require simple asynchronous coordination, others processing of event or stream-based data, and many deal with both. Your solution to this has a deep impact on your code.

“It’s not surprising that a multitude of solutions exist. Callbacks are a dumb simple way for passing single values around asynchronously, and promises are a more refined solution to the same problem. Event emitters and streams allow asynchronous handling of multiple values. FRP is a different approach which tackles streams and events more elegantly, but isn’t as good at asynchronous coordination. It can be overwhelming just to know where to start in all of this.” <br />
_By James Long. Posted on September 08, 2014_


### [ES6 Modules: The Final Syntax](http://www.2ality.com/2014/09/es6-modules-final.html "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/es6-modules-final.png" %}

“JavaScript does not have built-in support for modules, but the community has created impressive work-arounds. The two most important (and unfortunately incompatible) standards are CommonJS Modules ... [and] Asynchronous Module Definition (AMD)....

“The goal for ECMAScript 6 modules was to create a format that both users of CommonJS and of AMD are happy with.”<br />
_By Axel Rauschmayer. Published at 2ality.com on September 7, 2014_



<p>&nbsp; </p>

<small><a href="https://www.flickr.com/photos/gopalarathnam_v/48653786" style="text-decoration:none;">Photo</a> by Gopal Venkatesan, <em>Parrots - Jurong Bird Park</em>, <a href="https://creativecommons.org/licenses/by/2.0/">cc by 2.0</a></small>

<!-- a href="https://gist.github.com/ericelliott/d576f72441fc1b27dace" title="link to Eric Elliott gist"><img width="480px" src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/javascript/auxi/pix/essential/elliott-essential-js-links-gist.png" /></a  -->

<!--
{% include image.html url="media/2015-02-01-essential-js-links/cover.jpg" width="100%" description="No parrots!" %}
-->

