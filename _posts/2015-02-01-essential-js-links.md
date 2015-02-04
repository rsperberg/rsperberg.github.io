---
layout: post
title: Eric Elliott’s essential JavaScript links or The way of the parrot, not
post_author: Roger Sperberg
quote: How does the novice learner distinguish difficult-to-grasp concepts from inept explanations written by parrots?
image:
      url: /media/2015-02-01-essential-js-links/cover.jpg
video: false
---
<p><img src="/media/2015-02-01-essential-js-links/no-parrots-240.png" width="240px" style="float:left;" />There is a ton of learning material about JavaScript on the web,  and as a developer looking to achieve “mastery” in JavaScript, AngularJS and famo.us, I have buried myself under the weight of it, not always able to discern difficult-to-grasp concepts from inept explanations written by, well, parrots. (Who are these parrots? Facile developers who quickly picked up some framework — <i>I’m looking at you, Angular</i> — and who by way of explanation merely mouth the words others taught them without clarifying <i>why</i> something different is different or whether that difference is significant or not).</p>

Of course, my catholic intake of everything Angulared and JavaScripty has led me to lists curated by my elders, the first of which I present here. By “present” I actually mean _re-_present because this list of essential JavaScript links from Eric Elliott was posted as a GitHub gist by Elliott and is not only [still there](https://gist.github.com/ericelliott/d576f72441fc1b27dace title="link to Eric Elliott gist"), it regularly acquires fresh items.

I lack the credentials to dispute Elliott’s choices or to supplement them, but I hope my _re-_presentation is valuable by the addition of my own obsessive labors providing visuals of each link presented and a short summary or description that the site itself provides.

Elliott’s gist list is quickly scanned, despite its length (134 items at the end of January 2015). My bulky rendition is not. Rather the goal is to enable a quicker decision as to which resources to explore first by providing some sense of what each one is about.

Thanks to Eric Elliott for pointing out what sites we should be paying attention to. &nbsp; *—&nbsp;Roger Sperberg*

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
_By André Staltz. <span class="octicon octicon-star"></span>star:&nbsp;3,101 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;282_


### [A General Theory of Reactivity](https://github.com/kriskowal/gtor "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/general-theory-of-reactivity.png" %}

What is all this talk about reactive? Functional? Promises? This is the beginning of a reactive programming bible. “In the context of a computer program, reactivity is the process of receiving external stimuli and propagating events. This is a rather broad definition that covers a wide variety of topics. The term is usually reserved for systems that respond in turns to sensors, schedules, and above all, problems that exist between the chair and keyboard....

“[V]arious minds in the field of reactivity have been converging on a model that unifies at least promises and observables.” <br />
_By Kris Kowal. First posted at github on August 9, 2014. 5 contributors <span class="octicon octicon-star"></span>star:&nbsp;401 <br /><span class="octicon octicon-repo-forked"></span>fork:&nbsp;12_


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


## Required Viewing
### [Asynchronous Programming at Netflix](https://www.youtube.com/watch?v=gawmdhCNy-A "link to talk on YouTube") — [Jafar Husain](https://twitter.com/jhusain" "link to Jafar Husain on Twitter")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/asynchronous-programming.png" %}

“What does a mouse drag event have in common with an array of numbers? The answer to this question may surprise you: they are both collections. This insight holds the key to dramatically simplifying asynchronous programming in JavaScript. In this talk you will learn how you can use the familiar JavaScript Array methods to create surprisingly expressive asynchronous programs.” <br />
_By Jafar Husain. Delivered at @Scale 2014. Published on September 22, 2014. 5,560&nbsp;views_


### [Immutability: Putting The Dream Machine To Work](https://www.youtube.com/watch?v=SiFwRtCnxv4 "link to talk on YouTube") — [David Nolen](https://twitter.com/swannodette "link to David Nolen on Twitter")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/immutability.png" %}

“We live in a time of vast computational resources — many of us carry around in our pockets what just thirty years ago would have been considered a supercomputer. But it’s not just the hardware, these bite-sized supercomputers run software using state-of-the-art dynamic compilation techniques to deliver stellar performance without sacrificing flexibility.

“While all of this may sound incredibly futuristic, many of us still program these Dream Machines with miserly techniques not far removed from the best practices of the 1960s. <br />
_By David Nolen. Delivered at JSConf. Published on July 1, 2014. 5,168&nbsp;views_

### [Delivering the goods](https://www.youtube.com/watch?v=R8W_6xWphtw "link to YouTube video") — Paul Irish

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/delivering-the-goods.png" %}

One of the most important but overlooked topics in the development world today — page load times. <br />
_Keynote by Paul Irish. Delivered at Fluent 2014. Published on March&nbsp;13, 2014. 35,085&nbsp;views_


## Spec

### [ES5 Spec](http://es5.github.io/ "link to ES5 spec")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/annotated-es5.png"  %}

An annotated, hyperlinked version of the ES5 spec


### [ES6 draft](https://people.mozilla.org/%7Ejorendorff/es6-draft.html "link to draft spec")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/annotated-es6.png" %}

Most-recent draft of the ECMAScript 6 specification. <br />
_Version: Rev 31, January 15, 2014_


## Books

### [JavaScript for Kids](http://www.amazon.com/gp/product/B00QL616QE?ie=UTF8&amp;camp=213733&amp;creative=393177&amp;creativeASIN=B00QL616QE&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=6AOODC27L6URY3K2 "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/js-kids-combo.png" %}

Subtitled _A Playful Introduction to Programming_.  “A lighthearted introduction that teaches programming essentials through patient, step-by-step examples paired with funny illustrations.... Along the way, you’ll write games such as Find the Buried Treasure, Hangman, and Snake.... With visual examples like bouncing balls, animated bees, and racing cars, you can really see what you’re programming. Ages 10+” <br />
_By Nick Morgan. Published by No Starch Press in December 2014. ISBN: 978-1-59327-408-5. 336 pages_


### [Effective JavaScript](http://www.amazon.com/gp/product/0321812182?ie=UTF8&amp;camp=213733&amp;creative=393185&amp;creativeASIN=0321812182&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=JIC63I267I6UDQQZ "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/effectivejs.png" %}

Subtitled _68 Specific Ways to Harness the Power of JavaScript_. Uses a “scenario-driven style ... to explain the important concepts in JavaScript.” <br />
_By David Herman. Published by Pearson on December 6, 2012. ISBN-13: 978-0321812186. 200 pages_


### [Eloquent JavaScript](http://eloquentjavascript.net/ "link to version online")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/eloquent-js.png" %}

Free online edition.

“To some of us, writing computer programs is a fascinating game. A program is a building of thought. It is costless to build, it is weightless, and it grows easily under our typing hands.

“But without care, a program’s size and complexity will grow out of control, confusing even the person who created it. Keeping programs under control is the main problem of programming. When a program works, it is beautiful. The art of programming is the skill of controlling complexity. The great program is subdued, made simple in its complexity.” <br />
_By Marijn Haverbeke. Published by No Starch Press in December 2014. ISBN: 978-1-59327-584-6. 472 pages_


### [JavaScript: The Good Parts](http://www.amazon.com/gp/product/0596517742?ie=UTF8&amp;camp=213733&amp;creative=393185&amp;creativeASIN=0596517742&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=IJKESYSOTWGC27DR "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/js-good-parts.png" %}

“Crockford identifies the abundance of good ideas that make JavaScript an outstanding object-oriented programming language-ideas such as functions, loose typing, dynamic objects, and an expressive object literal notation. Unfortunately, these good ideas are mixed in with bad and downright awful ideas, like a programming model based on global variables.” <br />
_By Douglas Crockford. Published in May, 2008. ISBN13: 978-0596517748. 172 pages_


### [Programming JavaScript Applications](http://chimera.labs.oreilly.com/books/1234000000262 "link to version online")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/programming-js-apps.png" %}

Free online edition.

“In the real world, JavaScript applications are fragile, and when you change them things often break. Author Eric Elliott shows you how to add features without creating bugs or negatively impacting the rest of your code during the course of building a large JavaScript application.” <br />
_By Eric Elliott. Published by O’Reilly on June 22, 2014. ISBN13: 9781449320942. 300 pages_


### [JavaScript: The Definitive Guide](http://www.amazon.com/gp/product/0596805527?ie=UTF8&amp;camp=213733&amp;creative=393185&amp;creativeASIN=0596805527&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=AENIF5KLRQI3N335 "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/js-definitive-guide.png" %}

“A programmer’s guide and comprehensive reference to the core language and to the client-side JavaScript APIs defined by web browsers.... Covers HTML5 and ECMAScript 5.” <br />
_By David Flanagan. Sixth edition published by O’Reilly on May 13, 2011. ISBN: 9780596805531. 1096 pages_


### [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS "link to Github page for this series")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/You-Dont-Know-JS.png" %}

Prerelease (unedited) versions available at Github.

“Books in the _You Don’t Know JS_ series dive into trickier parts of the language that many JavaScript programmers simply avoid. Armed with this knowledge, you can achieve true JavaScript mastery.” <br />
_By Kyle Simpson. Published By O'Reilly. ‘Scope &amp; Closures,’ published in March 2014, print ISBN: 978-1-4493-3558-8, 98 pages.  ‘this &amp; Object Prototypes,’ July 2014, print ISBN:978-1-4919-0415-2, 174 pages. ‘Types &amp; Grammar,’ to be published in February 2015, print ISBN:978-1-4919-0419-0, 198 pages_


### [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read/ "link to LeanPub text for this book")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/understanding-ecmascript6.png" %}

Free to read online.

“ECMAScript 6 represents the biggest change to the core of JavaScript in the history of the language. Not only does the sixth edition add new object types, but also new syntax and exciting new capabilities. The result of years of study and debate, ECMAScript 6 reached feature complete status in 2014. While it will take a bit of time before all JavaScript environments support ECMAScript 6, it's still useful to understand what's coming and which features are available already.

“This book is a guide for the transition between ECMAScript 5 and 6. It is not specific to any JavaScript environment, so it is equally useful to web developers as it is Node.js developers.” <br />
_By Nicholas C. Zakas. Published by LeanPub. 30 percent complete in January 2015_


### [Node.js in Action](http://www.manning.com/cantelon/ "link to Manning page for this book")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/node-js-in-action.png" %}

“Dive into asynchronous programming, data storage, and output templating, and interact with the filesystem to create non-HTTP applications like TCP/IP servers and command-line tools. ... Requires basic knowledge of JavaScript.” <br />
_By Mike Cantelon, Marc Harter, T.J. Holowaychuk and Nathan Rajlich. Published by Manning on November 28, 2013. ISBN-13: 978-1617290572. 395 pages_


### [The Dream Machine: J.C.R. Licklider and the Revolution That Made Computing Personal](http://www.amazon.com/gp/product/0670899763?ie=UTF8&amp;camp=213733&amp;creative=393177&amp;creativeASIN=0670899763&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=NDUXYQOCMPC47SQI "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/the-dream-machine.png" %}

“An epic saga of technological advance that spans the history of modern computers from the Second World War to the explosion of creativity at Xerox PARC in the 1970s to the personal computer boom of the 1980s and the Internet boom of the 1990s.” <br />
_By M. Mitchell Waldrop. Published on August 27, 2001 by Viking (and in paperback in 2002 by Penguin)_

## Dev tools & collaboration


### [nvm](https://github.com/creationix/nvm "link to github site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/nvm.png" %}

**First install this...** “Simple bash script to manage multiple active node.js versions.”<br />
_Project of Tim Caswell. 105 contributors <span class="octicon octicon-star"></span>star:&nbsp;5,290 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;565_

### [Node](http://nodejs.org/ "link to nodejs.org website")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/nodejs-org.png" %}

**Then install Node (with nvm).** You'll need this even if you're a front-end dev.<br />
_583&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;34,408 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;7,665_


### [npm](https://www.npmjs.com/ "link to npmjs.org")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/npmjs.png" %}

**Install lots of other things with npm**,  _the_ package manager for JavaScript. Comes with Node. “npm makes it easy for JavaScript developers to share and reuse code, and it makes it easy to update the code that you're sharing.”<br />
_222&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;5,456 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;1,086_


### [Sublime Text 3](http://www.sublimetext.com/3 "link to info about ST3")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/sublime-text2.png" %}

“Sublime Text is a sophisticated text editor for code, markup and prose, [with a] slick user interface, extraordinary features and amazing performance.” ST3 was first released in beta in January 2013.<br />
_ST is developed by Jon Skinner._


### [Node Inspector](https://github.com/node-inspector/node-inspector "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/node-inspector.png" %}

Debug Node code with the Chrome debug tools, e.g., “a debugger interface for Node.js applications that uses the Blink Developer Tools (formerly WebKit Web Inspector).”<br />
_Project maintenance and support sponsored by <a href="http://strongloop.com/" title="link to strongloop.com">StrongLoop</a>. 38&nbsp;contributors <br /><span class="octicon octicon-star"></span>star:&nbsp;6,127 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;405_


### [TraceGL](https://github.com/traceglMPL/tracegl "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/traceGL.png" %}

Powerful runtime analysis of live JavaScript code. “traceGL transforms your JavaScript, injecting monitoring code that produces a log of everything that happens. This log is streamed from the target (node or browser), via the traceGL node.js process to the UI for visualisation. The UI tries to display the resulting huge amount of information fast, and uses webGL to render everything.”<br />
_<span class="octicon octicon-star"></span>star:&nbsp;216 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;29_


### [Tern](http://ternjs.net/ "link to Tern site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/ternjs.png" %}

Static analysis in JavaScript. “Tern is a stand-alone code-analysis engine for JavaScript. It is intended to be used with a code editor plugin to enhance the editor's support for intelligent JavaScript editing. Features include autocompletion of variables and properties and function argument hints.... Tern is capable of running both on node.js and in the browser.”<br />
_Project maintained by Marijn Haverbeke. 46&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;1,590 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;146_


### [JSDoc](http://usejsdoc.org/ "link to usejsdoc.org/")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/jsdoc.png" %}

Pair with <a href="http://ternjs.net/" rel="noreferrer" title="link to Tern site">Tern</a> for static analysis. “JSDoc 3 is an API documentation generator for JavaScript, similar to JavaDoc or PHPDoc. You add documentation comments directly to your source code, right alongside the code itself. The JSDoc Tool will scan your source code and generate a complete HTML documentation website for you.”<br />
_52&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;2,673 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;428_


### [Nitrous.IO](https://www.nitrous.io/join/uJcRo6yQDvs?utm_source=nitrous.io&amp;utm_medium=copypaste&amp;utm_campaign=referral "link to nitrous.io site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/nitrous.png" %}

(Supports live collaboration / pair programming) “Nitrous is a backend development platform which helps software developers save time by cutting out the repetitive parts of creating development environments and automating them.”


### [Slack](https://slack.com/ "link to slack site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/slack.png" %}

Chat for teams, with GitHub and Google hangouts integration. (For hangouts, just type /hangout in any channel.) “Slack is a platform for team communication: everything in one place, instantly searchable, available wherever you go.”


### [PrettyDiff](http://prettydiff.com/ "link to prettydiff site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/prettydiff.png" %}

“This tool was originally created to compare minified code by attaching a beautifier and minifier to a file comparison tool. Over the years it has grown into custom language parsers capable of performing a variety of language analysis. This application is 100% vanilla JavaScript and is API independent.”<br />
_3&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;275 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;31_


### [ES6 Fiddle](http://www.es6fiddle.net/ "link to es6fiddle site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/es6fiddle.png" %}

“Fiddlin' with ECMAScript6.” Includes sample code illustrating these ES6 aspects: arrow functions, block scope, classes and inheritance, default parameters, destructured assignment, generators, iterators, map, promises, rest parameters, set, spread operator and template literals.<br />
_A project of Jeff McRiffey. 2&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;31 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;6_

## Building

###[Browserify](http://browserify.org/ "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/browserify.png" %}

Bundle modules for the browser. “browserify is a tool for compiling node-flavored commonjs modules for the browser.

“You can use browserify to organize your code and use third-party libraries even if you don't use node itself in any other capacity except for bundling and installing packages with npm.

“The module system that browserify uses is the same as node, so packages published to npm that were originally intended for use in node but not browsers will work just fine in the browser too.

“Increasingly, people are publishing modules to npm which are intentionally designed to work in both node and in the browser using browserify and many packages on npm are intended for use in just the browser. [npm is for all javascript](http://maxogden.com/node-packaged-modules.html "link to post on using npm for client-side programs"), front or backend alike.” <br />
_Project of James Halliday. 133 contributors <span class="octicon octicon-star"></span>star:&nbsp;6,403 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;571_


###[How to use NPM as a Build Tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/ "link to post")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/use-npm-as-a-build-tool.png" %}

“npm has a great subset of functionality dedicated to running tasks to facilitate in a packages lifecycle — in other words, it is a great tool for build scripts.” <br />
_By Keith Cirkel. Posted on December 9, 2014_


### Lint / Quality checkers

### [JSHint](http://jshint.com/ "link to site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/jshint.png" %}

“JSHint scans a program written in JavaScript and reports about commonly made mistakes and potential bugs. The potential problem could be a syntax error, a bug due to implicit type conversion, a leaking variable or something else.

“Only 15% of all programs linted on this website pass the JSHint checks. In all other cases, JSHint finds some red flags that could’ve been bugs or potential problems.” <br />
_JSHint created and maintained by Anton Kovalyov. 183 contributors <span class="octicon octicon-star"></span>star:&nbsp;4,438 <br /><span class="octicon octicon-repo-forked"></span>fork:&nbsp;932_


### [ESLint](http://eslint.org/ "link to site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/eslint.png" %}

“ESLint is an open-source JavaScript linting utility.... JavaScript, being a dynamic and loosely-typed language, is especially prone to developer error. Without the benefit of a compilation process, JavaScript code is typically executed in order to find syntax or other errors. Linting tools like ESLint allow developers to discover problems with their JavaScript code without executing it.

“The primary reason ESLint was created was to allow developers to create their own linting rules. ESLint is designed to have all rules completely pluggable. The default rules are written just like any plugin rules would be. They can all follow the same pattern, both for the rules themselves as well as tests. ...

“ESLint is written using Node.js to provide a fast runtime environment and easy installation via npm.”<br />
_Created by Nicholas C. Zakas in June 2013. 121 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,524 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;254_


### [Istanbul](https://github.com/gotwarlost/istanbul "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/istanbul.png" %}

Code coverage reporting. <br />
_A project of Krishnan Anantheswaran. 36 contributors <span class="octicon octicon-star"></span>star:&nbsp;2,131 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;203_


### [tape](https://github.com/substack/tape "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/tape.png" %}

Use tape and faucet for dead simple unit testing. Tape is a “tap-producing test harness for node and browsers.” <br />
_A project of James Halliday. 23 contributors <span class="octicon octicon-star"></span>star:&nbsp;514 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;59_


### [faucet](https://github.com/substack/faucet "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/faucet.png" %}

Use tape and faucet for dead simple unit testing.  Faucet is a “human-readable TAP summarizer” <br />
_A project of James Halliday. 2 contributors <span class="octicon octicon-star"></span>star:&nbsp;173 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;3_

### [Nightwatch](http://nightwatchjs.org/) 

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/nightwatch.png" %}

Dead simple integration testing with Selenium: “Nightwatch.js is an easy-to-use Node.js-based End-to-End (E2E) testing solution for browser-based apps and websites.

“It uses the powerful Selenium WebDriver API to perform commands and assertions on DOM elements.”<br />
_A project of Andrei Rusu. 28 contributors <span class="octicon octicon-star"></span>star:&nbsp;2,530 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;180_

### Transpilers

### [6to5](https://github.com/6to5/6to5 "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/6to5.png" %}

(ES6) “6to5 turns ES6+ code into vanilla ES5, so you can use next-generation features today.”<br />
_44 contributors <span class="octicon octicon-star"></span>star:&nbsp;2,272 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;94_


### [CoffeeScript](http://coffeescript.org/ "link to coffeescript site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/coffeescript.png" %}

“CoffeeScript is a little language that compiles into JavaScript. Underneath that awkward Java-esque patina, JavaScript has always had a gorgeous heart. CoffeeScript is an attempt to expose the good parts of JavaScript in a simple way.

“The golden rule of CoffeeScript is: ‘It’s just JavaScript.’ The code compiles one-to-one into the equivalent JS, and there is no interpretation at runtime. You can use any existing JavaScript library seamlessly from CoffeeScript (and vice-versa). The compiled output is readable and pretty-printed, will work in every JavaScript runtime, and tends to run as fast or faster than the equivalent handwritten JavaScript.”<br />
_A project of Jeeremy Ashkenas. 167 contributors <span class="octicon octicon-star"></span>star:&nbsp;10,603 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;1,383_

### [Emscripten](http://kripken.github.io/emscripten-site/ "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/emscripten.png" %}

(frequently used for C/C++ JavaScript ports) “Practically any portable C or C++ codebase can be compiled into JavaScript using Emscripten, ranging from high-performance games that need to render graphics, play sounds, and load and process files, through to application frameworks like Qt.” <br />
_A project of Alon Zakai. 161 contributors <span class="octicon octicon-star"></span>star:&nbsp;7,751 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;850_


### [Traceur](https://github.com/google/traceur-compiler "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/traceur-compiler.png" %}

(ES.next) “Traceur is a JavaScript.next-to-JavaScript-of-today compiler that allows you to use features from the future today.... Traceur allows you to try out new and proposed language features today, helping you say what you mean in your code while informing the standards process.”<br />
_53 contributors <span class="octicon octicon-star"></span>star:&nbsp;4,388 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;259_


### [ES6 tools](https://github.com/addyosmani/es6-tools "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/es6-tools.png" %}

ES6 Tools list (112 listed in Jan 2015) <br />
_A project of Addy Osmani. 26 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,381 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;76_



## JavaScript environments

### [Node](http://nodejs.org/ "link to nodejs.org website")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/nodejs-org.png" %}

Server-side JavaScript and more <br />
_583 contributors <span class="octicon octicon-star"></span>star:&nbsp;34,408 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;7,665_



### [io.js](https://iojs.org/ )

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/io-js.png" %}

The Node fork.

“io.js is a JavaScript platform built on [Chrome’s V8 runtime](http://code.google.com/p/v8/ "link to V8 site"). This project began as a fork of [Joyent’s Node.js™](https://nodejs.org/ "link to nodejs.org") and is compatible with the [npm](https://www.npmjs.org/ "link to npmjs.org") ecosystem.

“Why? io.js aims to provide faster and predictable release cycles. It currently merges in the latest language, API and performance improvements to V8 while also updating libuv and other base libraries.

“This project aims to continue development of io.js under an ‘[open governance model](https://github.com/iojs/io.js/blob/v1.x/GOVERNANCE.md#readme "link to io.js project governance document")’ as opposed to corporate stewardship.”<br />
_626 contributors <span class="octicon octicon-star"></span>star:&nbsp;9,054 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;526_


## Libraries

### [es5-shim](https://github.com/es-shims/es5-shim "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/es5-shim.png" %}

“es5-shim.js and es5-shim.min.js monkey-patch a JavaScript context to contain all EcmaScript 5 methods that can be faithfully emulated with a legacy JavaScript engine.” Stable, production ready. <br />
_55 contributors <span class="octicon octicon-star"></span>star:&nbsp;3,379 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;467_


### [es6-shim](https://github.com/es-shims/es6-shim/ "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/es6-shim.png" %}

“Provides compatibility shims so that legacy JavaScript engines behave as closely as possible to ECMAScript 6 (Harmony).” Somewhat stable, but a few things I thought were solid got shifted to ES7. <br />
_29 contributors <span class="octicon octicon-star"></span>star:&nbsp;42 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;78_


### [es7-shim](https://www.npmjs.com/package/es7-shim "link to package site at npm")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/es7-shim.png" %}

“es7-shim.js exports an object that contains shims that can be used to monkeypatch a JavaScript context to contain all ECMAScript 7 methods that can be faithfully emulated with a legacy JavaScript engine.” Experimental. Use with caution.


### [native-promise-only](https://github.com/getify/native-promise-only "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/native-promise-only.png" %}

An ECMAScript-standard promise polyfill by <i>Kyle Simpson</i>. “The aim of this project is to be the smallest polyfill for Promises, staying as close as possible to what's specified in both Promises/A+ and the upcoming ES6 specification.”<br />
_A project of Kyle Simpson. <span class="octicon octicon-star"></span>star:&nbsp;255 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;16_


### [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/isomorphic-fetch.png" %}

A <a href="https://fetch.spec.whatwg.org/" rel="noreferrer">WHATWG fetch</a> standard polyfill <br />
_By Matt Andrews. 3 contributors <span class="octicon octicon-star"></span>star:&nbsp;32 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;3_


### [jQuery](http://jquery.com/ "link to jQuery site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/jquery.png" %}

Yes, I [still use jQuery](https://docs.google.com/document/d/1LPaPA30bLUB_publLIMF0RlhdnPx_ePXm7oW02iiT6o/ "link to post") and so do 61% of the top 100,000 websites — for good reason.<br />
_213 contributors <span class="octicon octicon-star"></span>star:&nbsp;33,188 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;7,855_


### [Blaze](http://meteor.github.io/blaze/ "link to Blaze website")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/blaze.png" %}

DOM-diffing isomorphic reactive templates from Meteor. “HTML templating is central to web applications. With Blaze, Meteor's live page update technology, you can render your HTML reactively, meaning that it will update automatically to track changes in the data used to generate it.”<br />
_2 contributors <span class="octicon octicon-star"></span>star:&nbsp;69 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;9_


### [RxJS](https://github.com/Reactive-Extensions/RxJS link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/reactive.png" %}

Reactive extensions for JavaScript. [What’s reactive?](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4 "link to article, 'The two pillars of JS' ") <br />
_91 contributors <span class="octicon octicon-star"></span>star:&nbsp;2,952 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;275_


### [Moment](http://momentjs.com )

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/moment.png" %}

A lightweight JavaScript date library for parsing, validating, manipulating, and formatting dates. Includes 81 locale/script/language combinations. “Moment was designed to work both in the browser and in Node.JS. All code will work in both environments. All unit tests are run in both environments.” <br />
_233 contributors <span class="octicon octicon-star"></span>star:&nbsp;19,362 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;2,009_


### [Globalize](https://github.com/jquery/globalize link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/globalize.png" %}

i18n / translate your app for many languages and locations (locales). “Each language, and the countries that speak that language, have different expectations when it comes to how numbers (including currency and percentages) and dates should appear. Obviously, each language has different names for the days of the week and the months of the year. But they also have different expectations for the structure of dates, such as what order the day, month and year are in. In number formatting, not only does the character used to delineate number groupings and the decimal portion differ, but the placement of those characters differ as well.

“A user using an application should be able to read and write dates and numbers in the format they are accustomed to. This library makes this possible, providing an API to convert user-entered number and date strings — in their own format — into actual numbers and dates, and conversely, to format numbers and dates into that string format.” <br />
_26 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,475 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;331_


### [Express](http://expressjs.com/ )

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/express.png" %}

The most popular framework for Node. “A fast, un-opinionated, minimalist web framework for Node.js applications.” <br />
_87 contributors <span class="octicon octicon-star"></span>star:&nbsp;362 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;232_


### [Stampit](https://github.com/ericelliott/stampit link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/stampit.png" %}

Stampit — create objects from reusable, composable behaviors. Prototypal inheritance with stamps. <br />
_A project of Eric Elliott. 9 contributors <span class="octicon octicon-star"></span>star:&nbsp;651 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;38_


### [Credential](https://github.com/ericelliott/credential "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/credential.png" %}

If you write Node apps with password logins, you need Credential: “Easy password hashing and verification in Node. Protects against brute force, rainbow tables, and timing attacks.”<br />
_A project of Eric Elliott. 6&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;135 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;8_


### [cuid](https://github.com/ericelliott/cuid "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/cuid.png" %}

GUIDs are broken — use cuid, instead. “Collision-resistant ids optimized for horizontal scaling and performance.”<br />
_A project of Eric Elliott. 4&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;218 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;8_


### [Velocity](http://julian.com/research/velocity/ "link to Velocity site")
 &amp; [Velocity Motion Designer (VMD)](ttp://julian.com/research/velocity/#vmd "link to VMD section")
 
{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/velocity.png" %}

UI animation library: “Velocity is an animation engine with the same API as jQuery's <code>$.animate()</code>. It works with and without jQuery. It’s incredibly fast, and it features color animation, transforms, loops, easings, SVG support, and scrolling. It is the best of jQuery and CSS transitions combined.”<br />
_A project of Julian Shapiro. 14&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;6,567 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;514_


### [json-schema](https://github.com/kriszyp/json-schema "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/json-schema.png" %}

Great for model validations: “JSON Schema describes your JSON data format.”<br />
_12&nbsp;contributors (at github.com/json-schema)<span class="octicon octicon-star"></span>star:&nbsp;438 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;95_





<p>&nbsp; </p>

<small><a href="https://www.flickr.com/photos/pbekesi/392765048" style="text-decoration:none;">Photo</a> by Peter Békési, <a href="https://creativecommons.org/licenses/by-nc-sa/2.0/">CC BY-NC-SA 2.0)</a></small>

<!--  small><a href="https://www.flickr.com/photos/gopalarathnam_v/48653786" style="text-decoration:none;">Photo</a> by Gopal Venkatesan, <em>Parrots - Jurong Bird Park</em>, <a href="https://creativecommons.org/licenses/by/2.0/">cc by 2.0</a></small  -->

<!-- a href="https://gist.github.com/ericelliott/d576f72441fc1b27dace" title="link to Eric Elliott gist"><img width="480px" src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/javascript/auxi/pix/essential/elliott-essential-js-links-gist.png" /></a  -->

<!--
{% include image.html url="media/2015-02-01-essential-js-links/cover.jpg" width="100%" description="No parrots!" %}
-->
<!-- Peter Békési 2007-0204  Attribution-NonCommercial-ShareAlike 2.0 Generic (CC BY-NC-SA 2.0) https://www.flickr.com/photos/pbekesi/392765048  -->
