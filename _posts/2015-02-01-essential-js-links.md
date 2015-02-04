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

Thanks to Eric Elliott for pointing out what sites we should be paying attention to. &nbsp; *—Roger Sperberg*

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
_By Kris Kowal. First posted at github on August 9, 2014. 5 contributors <span class="octicon octicon-star"></span>star:&nbsp;401 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;12_


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
_By Jafar Husain. Delivered at @Scale 2014. Published on September 22, 2014. 5,560 views_


### [Immutability: Putting The Dream Machine To Work](https://www.youtube.com/watch?v=SiFwRtCnxv4 "link to talk on YouTube") — [David Nolen](https://twitter.com/swannodette "link to David Nolen on Twitter")

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/immutability.png" %}

“We live in a time of vast computational resources — many of us carry around in our pockets what just thirty years ago would have been considered a supercomputer. But it’s not just the hardware, these bite-sized supercomputers run software using state-of-the-art dynamic compilation techniques to deliver stellar performance without sacrificing flexibility.

“While all of this may sound incredibly futuristic, many of us still program these Dream Machines with miserly techniques not far removed from the best practices of the 1960s. <br />
_By David Nolen. Delivered at JSConf. Published on Jul 1, 2014. 5,168 views_

### [Delivering the goods](https://www.youtube.com/watch?v=R8W_6xWphtw "link to YouTube video") — Paul Irish

{% include image-no-descrip.html url="/media/2015-02-01-essential-js-links/delivering-the-goods.png" %}

One of the most important but overlooked topics in the development world today — page load times. <br />
_Keynote by Paul Irish. Delivered at Fluent 2014. Published on March 13, 2014. 35,085 views_


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
_Project maintenance and support sponsored by <a href="http://strongloop.com/" title="link to strongloop.com">StrongLoop</a>. 38&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;6,127 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;405_


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





<p>&nbsp; </p>

<small><a href="https://www.flickr.com/photos/pbekesi/392765048" style="text-decoration:none;">Photo</a> by Peter Békési, <em>Parrots - Jurong Bird Park</em>, <a href="https://creativecommons.org/licenses/by-nc-sa/2.0/">CC BY-NC-SA 2.0)</a></small>

<!--  small><a href="https://www.flickr.com/photos/gopalarathnam_v/48653786" style="text-decoration:none;">Photo</a> by Gopal Venkatesan, <em>Parrots - Jurong Bird Park</em>, <a href="https://creativecommons.org/licenses/by/2.0/">cc by 2.0</a></small  -->

<!-- a href="https://gist.github.com/ericelliott/d576f72441fc1b27dace" title="link to Eric Elliott gist"><img width="480px" src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/javascript/auxi/pix/essential/elliott-essential-js-links-gist.png" /></a  -->

<!--
{% include image.html url="media/2015-02-01-essential-js-links/cover.jpg" width="100%" description="No parrots!" %}
-->
<!-- Peter Békési 2007-0204  Attribution-NonCommercial-ShareAlike 2.0 Generic (CC BY-NC-SA 2.0) https://www.flickr.com/photos/pbekesi/392765048  -->
