---
layout: post
title: Eric Elliott’s essential JavaScript links or The way of the parrot, not
hcolor: '#eeeeee'
post_author: Roger Sperberg
quote: How does the novice learner distinguish difficult-to-grasp concepts from inept explanations written by parrots? Follow an expert’s directions.
image:
      url: /media/2015-02-15-essential-js-links/cover.jpg
video: false
---
<p><img src="/media/2015-02-15-essential-js-links/no-parrots-240.png" width="240px" style="float:left;" />There is a ton of learning material about JavaScript on the web,  and as a developer looking to achieve “mastery” in JavaScript, AngularJS and famo.us, I have buried myself under the weight of it, not always able to discern difficult-to-grasp concepts from inept explanations written by, well, parrots. (Who are these parrots? Facile developers who quickly picked up some framework — <i>I’m looking at you, Angular</i> — and who by way of explanation merely mouth the words others taught them without clarifying <i>why</i> something different is different or whether that difference is significant or not).</p>

Of course, my catholic intake of everything Angulared and JavaScripty has led me to lists curated by my elders, the first of which I present here. By “present” I actually mean _re-_present because this list of essential JavaScript links from Eric Elliott (the author of  [Programming JavaScript Applications](http://pjabook.com "link to book page at ericelliottjs.com")) was posted as a GitHub gist by Elliott and is not only [still there](https://gist.github.com/ericelliott/d576f72441fc1b27dace"link to Eric Elliott gist"), it regularly acquires fresh items.

His compilation demonstrates an awareness of knowledgeable guides, right-minded attitudes and information that must be paid attention to, all while making clear that he does not gladly suffer fools, slovenly thinking or the misguided parroting of out-dated principles.

That’s what I like about this list.

Of course, I lack the experience to dispute Elliott’s choices or even to supplement them, but I hope nonetheless that my _re-_presentation is valuable by the addition of my own obsessive labors providing visuals of each link presented and a short summary or self-description that the site itself provides.

Elliott’s gist list is quickly scanned, despite its length (141 items in mid-February 2015). My bulky rendition is not. But I’ve kept the list as a single post and not divided it into two or three pieces to enable a quicker decision as to which resources to explore first by providing some sense of what each one is about.

So herewith I offer thanks to Eric Elliott for pointing out what sites we should be paying attention to. &nbsp; *—&nbsp;Roger Sperberg*

<hr />

_PS: If you know of other valuable JavaScript resources, please suggest them at the original [source gist](https://gist.github.com/ericelliott/d576f72441fc1b27dace "link to Eric Elliott gist"). I will endeavor to keep this annotated list in sync with it._

<p>&nbsp; </p>

## <a name="required-reading-online-resources"></a>Required Reading (Online resources)

### [Learn JavaScript Essentials (for all skill levels)](https://medium.com/javascript-scene/learn-javascript-b631a4af11f2 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/learn-javascript.png" %}

One clear path to JavaScript mastery. <br />
_By Eric Elliot. Published at medium.com on August 2, 2014_

### [JavaScript Training Sucks](https://medium.com/javascript-scene/javascript-training-sucks-284b53666245 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/javascript-training-sucks.png" %}

99 out of 100 JS developers lack the skills they need to fill hundreds of thousands of jobs. We can change that. <br />
_By Eric Elliot. Published at medium.com on December 29, 2014_


### [How to Fix the `class` Keyword](https://medium.com/p/how-to-fix-the-es6-class-keyword-2d42bb3f4caf)

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/how-to-fix-es6-class-keyword.png" %}

TL;DR `class` is broken. Don’t use it until it’s fixed.<br />
_By Eric Elliot. Published at medium.com on March 3, 2015_


### [The Two Pillars of JavaScript Part 1: Prototypal OO](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/the-two-pillars-of-javascript-pt-1.png" %}

“You never need classes in JavaScript, and I have never seen a situation where class is a better approach than the alternatives.” <br />
_By Eric Elliot. Published at medium.com on October 21, 2014_


### [The Two Pillars of JavaScript Part 2: Functional Programming](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4 "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/the-two-pillars-of-javascript-pt-2.png" %}

“Closures are a mechanism for containing state. In JavaScript, a closure is created whenever a function accesses a variable defined outside the immediate function scope. It’s easy to create closures: Simply define a function inside another function, and expose the inner function, either by returning it, or passing it into another function. The variables used by the inner function will be available to it, even after the outer function has finished running.” <br />
_By Eric Elliot. Published at medium.com on December 12, 2014_

### [JavaScript Objects](http://davidwalsh.name/javascript-objects "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/javascript-objects.png" %}

An excellent explanation of inheritance in JavaScript. “JavaScript has been plagued since the beginning with misunderstanding and awkwardness around its ‘prototypal inheritance’ system, mostly due to the fact that ‘inheritance’ isn’t how JS works at all, and trying to do that only leads to gotchas and confusions that we have to pave over with user-land helper libs. Instead, embracing that JS has ‘behavior delegation’ (merely delegation links between objects) fits naturally with how JS syntax works, which creates more sensible code without the need of helpers.” <br />
_By Kyle Simpson. Published at davidwalsh.com on April 22, 2013_


### [Isomorphic JavaScript](http://isomorphic.net/ "link to isomorphic.net")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/isomorphic.png" %}

“Isomorphic JavaScript apps are JavaScript applications that can run both client-side and server-side.
The backend and frontend share the same code.”


### [JavaScript Application Architecture on the Road to 2015](https://medium.com/@addyosmani/javascript-application-architecture-on-the-road-to-2015-d8125811101b "link to article at medium.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/javascript-application-architecture.png" %}

“On an architectural level, the way we craft large-scale applications in JavaScript has changed in at least one fundamental way in the last few years. Once you remove the minutia of machinery bringing forth unidirectional data-binding, immutable data-structures and virtual-DOM (all of which are interesting problem spaces) the one key concept that many devs seem to have organically converged on is composition. Composition is incredibly powerful, allowing us to stitch together reusable pieces of functionality to ‘compose’ a larger application....

“Note: earlier players in the JS framework game (Dojo, YUI, ExtJS) touted composition strongly and it’s been around forever but it’s taken us a while for most people to grok the true power of this model as broadly on the front-end.” <br />
_By Addy Osmani. Published at medium.com on December 15, 2014_


### [Reactive MVC and the Virtual DOM](http://futurice.com/blog/reactive-mvc-and-the-virtual-dom "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/reactive-mvc-and-the-virtual-dom.png" %}

Great read, even if you’re not a React user. “The new great idea in React is Virtual DOM Rendering. The gist is to frequently re-render a complete and lightweight representation of the DOM, then apply a difference filter to detect the minimum changes that need to be made to the DOM. A similar technique has existed in game development long before React: re-render the game screen in every game loop, but only update the minimum portion of the screen which changed compared to the previously rendered screen.” <br />
_By Andre Medeiros. Published at Futurice on November 2, 2014_


### [The introduction to Reactive Programming you’ve been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754 "link to gist")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/introrx.png" %}

“Reactive programming is programming with asynchronous data streams.

“In a way, this isn’t anything new. Event buses or your typical click events are really an asynchronous event stream, on which you can observe and do some side effects. Reactive is that idea on steroids. You are able to create data streams of anything, not just from click and hover events. Streams are cheap and ubiquitous, anything can be a stream: variables, user inputs, properties, caches, data structures, etc. For example, imagine your Twitter feed would be a data stream in the same fashion that click events are. You can listen to that stream and react accordingly.” <br />
_By André Staltz. <span class="octicon octicon-star"></span>star:&nbsp;3,169 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;286_


### [A General Theory of Reactivity](https://github.com/kriskowal/gtor "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/general-theory-of-reactivity.png" %}

What is all this talk about reactive? Functional? Promises? This is the beginning of a reactive programming bible. “In the context of a computer program, reactivity is the process of receiving external stimuli and propagating events. This is a rather broad definition that covers a wide variety of topics. The term is usually reserved for systems that respond in turns to sensors, schedules, and above all, problems that exist between the chair and keyboard....

“[V]arious minds in the field of reactivity have been converging on a model that unifies at least promises and observables.” <br />
_By Kris Kowal. First posted at github on August 9, 2014. 5 contributors <span class="octicon octicon-star"></span>star:&nbsp;416 <br /><span class="octicon octicon-repo-forked"></span>fork:&nbsp;14_


### [ES6 Generators](http://davidwalsh.name/es6-generators "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/es6-generators.png" %}

A series of blog posts on ES6 generators: “Whether you realized it or not, you’ve always been able to assume something fairly fundamental about your functions: once the function starts running, it will always run to completion before any other JS code can run....

“With ES6 generators, we have a different kind of function, which may be paused in the middle, one or many times, and resumed later, allowing other code to run during these paused periods.” <br />
_By Kyle Simpson. Published at davidwalsh.com, July – August 2014_


### [Typed JavaScript](http://www.2ality.com/2014/10/typed-javascript.html "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/typed-javascript.png" %}

Excellent post about the state of typed JavaScript via Microsoft’s TypeScript, Facebook’s Flow and Google’s AtScript. <br />
_By Axel Rauschmayer. Published at 2ality  and updated on November 18, 2014_


### [Taming the Asynchronous Beast with CSP in JavaScript](http://jlongster.com/Taming-the-Asynchronous-Beast-with-CSP-in-JavaScript "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/Taming-the-Asynchronous-Beast.png" %}

“Every piece of software deals with complex control flow mechanisms like callbacks, promises, events, and streams. Some require simple asynchronous coordination, others processing of event or stream-based data, and many deal with both. Your solution to this has a deep impact on your code.

“It’s not surprising that a multitude of solutions exist. Callbacks are a dumb simple way for passing single values around asynchronously, and promises are a more refined solution to the same problem. Event emitters and streams allow asynchronous handling of multiple values. FRP is a different approach which tackles streams and events more elegantly, but isn’t as good at asynchronous coordination. It can be overwhelming just to know where to start in all of this.” <br />
_By James Long. Posted on September 08, 2014_


### [ES6 Modules: The Final Syntax](http://www.2ality.com/2014/09/es6-modules-final.html "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/es6-modules-final.png" %}

“JavaScript does not have built-in support for modules, but the community has created impressive work-arounds. The two most important (and unfortunately incompatible) standards are CommonJS Modules ... [and] Asynchronous Module Definition (AMD)....

“The goal for ECMAScript 6 modules was to create a format that both users of CommonJS and of AMD are happy with.”<br />
_By Axel Rauschmayer. Published at 2ality.com on September 7, 2014_







<!--  ===============================================================================  -->
<!--  ===============================================================================  -->


## <a name="required-viewing"></a>Required Viewing

### [Classical Inheritance is Obsolete: How to Think in Prototypal OO](https://vimeo.com/69255635 "link to video on vimeo")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/classical-inheritance.png" %}

“Learn about the limitations of classical inheritance, and the power and flexibility of prototypal OO that exists natively in JavaScript.
* How to inherit from multiple ancestors
* How to inherit privileged members and private state
* How to compose objects and object factories”

_A talk given by [Eric Elliott](https://twitter.com/_ericelliott "link to @\_ericelliott twitter page") at O’Reilly’s Fluent Conference: JavaScript and Beyond, 2013. Length: 43:18_


### [Asynchronous Programming at Netflix](https://www.youtube.com/watch?v=gawmdhCNy-A "link to talk on YouTube") — [Jafar Husain](https://twitter.com/jhusain" "link to Jafar Husain on Twitter")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/asynchronous-programming.png" %}

“What does a mouse drag event have in common with an array of numbers? The answer to this question may surprise you: they are both collections. This insight holds the key to dramatically simplifying asynchronous programming in JavaScript. In this talk you will learn how you can use the familiar JavaScript Array methods to create surprisingly expressive asynchronous programs.” <br />
_By Jafar Husain. Delivered at @Scale 2014. Published on September 22, 2014. Length: 41:46, 5,823&nbsp;views_


### [Immutability: Putting The Dream Machine To Work](https://www.youtube.com/watch?v=SiFwRtCnxv4 "link to talk on YouTube") — [David Nolen](https://twitter.com/swannodette "link to David Nolen on Twitter")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/immutability.png" %}

“We live in a time of vast computational resources — many of us carry around in our pockets what just thirty years ago would have been considered a supercomputer. But it’s not just the hardware, these bite-sized supercomputers run software using state-of-the-art dynamic compilation techniques to deliver stellar performance without sacrificing flexibility.

“While all of this may sound incredibly futuristic, many of us still program these Dream Machines with miserly techniques not far removed from the best practices of the 1960s. <br />
_By David Nolen. Delivered at JSConf. Published on July 1, 2014. Length: 22:05, 5,348&nbsp;views_


### [Delivering the goods](https://www.youtube.com/watch?v=R8W_6xWphtw "link to YouTube video") — Paul Irish

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/delivering-the-goods.png" %}

One of the most important but overlooked topics in the development world today — page load times: “[A]nd finally answering the ‘page size vs # of requests’ question...”<br />
_Keynote by [Paul Irish](https://twitter.com/paul_irish "link to @paul_irish twitter page"). Delivered at Fluent 2014. Published on March&nbsp;13, 2014. Length: 23:24, 35,357&nbsp;views_


### [Immutable Data and React](https://www.youtube.com/watch?v=I7IdS-PbEgI&list=PLb0IAmt7-GS1cbw4qonlQztYV1TAW0sCr "link to YouTube video")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/immutable-data-and-react.png" %}

“Immutable data unlocks powerful memoization techniques and prohibits accidental coupling via shared mutable state. It’s no accident that these are the the same benefits provided by React.

“Persistent data structures provide the benefits of immutability while maintaining high performance reads and writes and present a familiar API.

“Learn about how persistent immutable data structures work, and techniques for using them in your React applications with Immutable.js, a library of fully persistent immutable data structures.”<br />
_Given by [Lee Byron](https://twitter.com/leeb "link to @leeb twitter page") at React.js Conf 2015, January 29, 2015. Length: 31:10, 11,592 views_


### [Simplicity Matters](https://www.youtube.com/watch?v=rI8tNMsozo0 "link to YouTube video")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/simplicity-matters.png" %}

A later version of the influential talk “Simple Made Easy”: “Simplicity is prerequisite to reliability — Edsger Dijkstra”<br />
_Keynote by [Rich Hickey](https://twitter.com/richhickey "link to @richhickey twitter page"). Delivered at RailsConf2012, April 23, 2012. Length: 36:53, 41,062 views_







<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="spec"></a>Spec

### [ES5 Spec](http://es5.github.io/ "link to ES5 spec")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/annotated-es5.png" %}

An annotated, hyperlinked version of the ES5 spec


### [ES6 draft](https://people.mozilla.org/%7Ejorendorff/es6-draft.html "link to draft spec")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/annotated-es6.png" %}

Most-recent draft of the ECMAScript 6 specification. <br />
_Version: Rev 32, February 2, 2015_




<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="books"></a>Books

### [<a name="javascript-for-kids"></a>JavaScript for Kids](http://www.amazon.com/gp/product/B00QL616QE?ie=UTF8&amp;camp=213733&amp;creative=393177&amp;creativeASIN=B00QL616QE&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=6AOODC27L6URY3K2 "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/js-kids-combo.png" %}

Subtitled _A Playful Introduction to Programming_.  “A lighthearted introduction that teaches programming essentials through patient, step-by-step examples paired with funny illustrations.... Along the way, you’ll write games such as Find the Buried Treasure, Hangman, and Snake.... With visual examples like bouncing balls, animated bees, and racing cars, you can really see what you’re programming. Ages 10+” <br />
_By Nick Morgan. Published by No Starch Press in December 2014. ISBN: 978-1-59327-408-5. 336 pages_


### [Eloquent JavaScript](http://eloquentjavascript.net/ "link to version online")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/eloquent-js.png" %}

Free online edition.

“To some of us, writing computer programs is a fascinating game. A program is a building of thought. It is costless to build, it is weightless, and it grows easily under our typing hands.

“But without care, a program’s size and complexity will grow out of control, confusing even the person who created it. Keeping programs under control is the main problem of programming. When a program works, it is beautiful. The art of programming is the skill of controlling complexity. The great program is subdued, made simple in its complexity.” <br />
_By Marijn Haverbeke. Published by No Starch Press in December 2014. ISBN: 978-1-59327-584-6. 472 pages_


### [JavaScript: The Good Parts](http://www.amazon.com/gp/product/0596517742?ie=UTF8&amp;camp=213733&amp;creative=393185&amp;creativeASIN=0596517742&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=IJKESYSOTWGC27DR "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/js-good-parts.png" %}

“Crockford identifies the abundance of good ideas that make JavaScript an outstanding object-oriented programming language-ideas such as functions, loose typing, dynamic objects, and an expressive object literal notation. Unfortunately, these good ideas are mixed in with bad and downright awful ideas, like a programming model based on global variables.” <br />
_By Douglas Crockford. Published in May, 2008. ISBN13: 978-0596517748. 172 pages_


### [Effective JavaScript](http://www.amazon.com/gp/product/0321812182?ie=UTF8&amp;camp=213733&amp;creative=393185&amp;creativeASIN=0321812182&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=JIC63I267I6UDQQZ "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/effectivejs.png" %}

Subtitled _68 Specific Ways to Harness the Power of JavaScript_. Uses a “scenario-driven style ... to explain the important concepts in JavaScript.” <br />
_By David Herman. Published by Pearson on December 6, 2012. ISBN-13: 978-0321812186. 200 pages_


### [Programming JavaScript Applications](http://pjabook.com "link to book page at ericelliottjs.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/programming-js-apps-ericelliott.png" %}

Link to the print-plus-ebook bundle for this book.  (There is also an [online](http://chimera.labs.oreilly.com/books/1234000000262 "link to version online") version of this title.)

“In the real world, JavaScript applications are fragile, and when you change them things often break. Author Eric Elliott shows you how to add features without creating bugs or negatively impacting the rest of your code during the course of building a large JavaScript application.” <br />
_By Eric Elliott. Published by O’Reilly on June 22, 2014. ISBN13: 9781449320942. 300 pages_


### [JavaScript: The Definitive Guide](http://www.amazon.com/gp/product/0596805527?ie=UTF8&amp;camp=213733&amp;creative=393185&amp;creativeASIN=0596805527&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=AENIF5KLRQI3N335 "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/js-definitive-guide.png" %}

“A programmer’s guide and comprehensive reference to the core language and to the client-side JavaScript APIs defined by web browsers.... Covers HTML5 and ECMAScript 5.” <br />
_By David Flanagan. Sixth edition published by O’Reilly on May 13, 2011. ISBN: 9780596805531. 1096 pages_


### [You Don’t Know JS](https://github.com/getify/You-Dont-Know-JS "link to Github page for this series")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/You-Dont-Know-JS.png" %}

Prerelease (unedited) versions available at Github.

“Books in the _You Don’t Know JS_ series dive into trickier parts of the language that many JavaScript programmers simply avoid. Armed with this knowledge, you can achieve true JavaScript mastery.” <br />
_By Kyle Simpson. Published By O’Reilly. ‘Scope &amp; Closures,’ published in March 2014, print ISBN: 978-1-4493-3558-8, 98 pages.  ‘this &amp; Object Prototypes,’ July 2014, print ISBN:978-1-4919-0415-2, 174 pages. ‘Types &amp; Grammar,’ to be published in February 2015, print ISBN:978-1-4919-0419-0, 198 pages_


### [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read/ "link to LeanPub text for this book")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/understanding-ecmascript6.png" %}

Free to read online.

“ECMAScript 6 represents the biggest change to the core of JavaScript in the history of the language. Not only does the sixth edition add new object types, but also new syntax and exciting new capabilities. The result of years of study and debate, ECMAScript 6 reached feature complete status in 2014. While it will take a bit of time before all JavaScript environments support ECMAScript 6, it’s still useful to understand what’s coming and which features are available already.

“This book is a guide for the transition between ECMAScript 5 and 6. It is not specific to any JavaScript environment, so it is equally useful to web developers as it is Node.js developers.” <br />
_By Nicholas C. Zakas. Published by LeanPub. 30 percent complete in January 2015_


### [Node.js in Action](http://www.manning.com/cantelon/ "link to Manning page for this book")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/node-js-in-action.png" %}

“Dive into asynchronous programming, data storage, and output templating, and interact with the filesystem to create non-HTTP applications like TCP/IP servers and command-line tools. ... Requires basic knowledge of JavaScript.” <br />
_By Mike Cantelon, Marc Harter, T.J. Holowaychuk and Nathan Rajlich. Published by Manning on November 28, 2013. ISBN-13: 978-1617290572. 395 pages_


### [The Dream Machine: J.C.R. Licklider and the Revolution That Made Computing Personal](http://www.amazon.com/gp/product/0670899763?ie=UTF8&amp;camp=213733&amp;creative=393177&amp;creativeASIN=0670899763&amp;linkCode=shr&amp;tag=ericleads-20&amp;linkId=NDUXYQOCMPC47SQI "link to Amazon page for this book")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/the-dream-machine.png" %}

“An epic saga of technological advance that spans the history of modern computers from the Second World War to the explosion of creativity at Xerox PARC in the 1970s to the personal computer boom of the 1980s and the Internet boom of the 1990s.” <br />
_By M. Mitchell Waldrop. Published on August 27, 2001 by Viking (and in paperback in 2002 by Penguin)_








<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="dev-tools-collaboration"></a>Dev tools & collaboration


### [nvm](https://github.com/creationix/nvm "link to github site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nvm.png" %}

**First install this...** “Simple bash script to manage multiple active node.js versions.”<br />
_Project of Tim Caswell. 107 contributors <span class="octicon octicon-star"></span>star:&nbsp;5,465 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;574_


### [Node](http://nodejs.org/ "link to nodejs.org website")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nodejs-org.png" %}

**Then install Node (with nvm).** You’ll need this even if you’re a front-end dev.<br />
_585&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;34,655 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;7,718_


### [npm](https://www.npmjs.com/ "link to npmjs.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/npmjs.png" %}

**Install lots of other things with npm**,  _the_ package manager for JavaScript. Comes with Node. “npm makes it easy for JavaScript developers to share and reuse code, and it makes it easy to update the code that you’re sharing.”<br />
_226&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;5,539 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;1,108_


### [Sublime Text 3](http://www.sublimetext.com/3 "link to info about ST3")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/sublime-text2.png" %}

“Sublime Text is a sophisticated text editor for code, markup and prose, [with a] slick user interface, extraordinary features and amazing performance.” ST3 was first released in beta in January 2013.<br />
_ST is developed by Jon Skinner._


### [Node Inspector](https://github.com/node-inspector/node-inspector "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/node-inspector.png" %}

Debug Node code with the Chrome debug tools, e.g., “a debugger interface for Node.js applications that uses the Blink Developer Tools (formerly WebKit Web Inspector).”<br />
_Project maintenance and support sponsored by <a href="http://strongloop.com/" title="link to strongloop.com">StrongLoop</a>. 38&nbsp;contributors <br /><span class="octicon octicon-star"></span>star:&nbsp;6,200 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;407_


### [TraceGL](https://github.com/traceglMPL/tracegl "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/traceGL.png" %}

Powerful runtime analysis of live JavaScript code. “traceGL transforms your JavaScript, injecting monitoring code that produces a log of everything that happens. This log is streamed from the target (node or browser), via the traceGL node.js process to the UI for visualisation. The UI tries to display the resulting huge amount of information fast, and uses webGL to render everything.”<br />
_<span class="octicon octicon-star"></span>star:&nbsp;222 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;29_


### [Tern](http://ternjs.net/ "link to Tern site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/ternjs.png" %}

Static analysis in JavaScript. “Tern is a stand-alone code-analysis engine for JavaScript. It is intended to be used with a code editor plugin to enhance the editor’s support for intelligent JavaScript editing. Features include autocompletion of variables and properties and function argument hints.... Tern is capable of running both on node.js and in the browser.”<br />
_Project maintained by Marijn Haverbeke. 46&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;1,607 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;148_


### [JSDoc](http://usejsdoc.org/ "link to usejsdoc.org/")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/jsdoc.png" %}

Pair with <a href="http://ternjs.net/" rel="noreferrer" title="link to Tern site">Tern</a> for static analysis. “JSDoc 3 is an API documentation generator for JavaScript, similar to JavaDoc or PHPDoc. You add documentation comments directly to your source code, right alongside the code itself. The JSDoc Tool will scan your source code and generate a complete HTML documentation website for you.”<br />
_53&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;2,732 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;437_


### [Nitrous.IO](https://www.nitrous.io/join/uJcRo6yQDvs?utm_source=nitrous.io&amp;utm_medium=copypaste&amp;utm_campaign=referral "link to nitrous.io site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nitrous.png" %}

(Supports live collaboration / pair programming) “Nitrous is a backend development platform which helps software developers save time by cutting out the repetitive parts of creating development environments and automating them.”


### [Slack](https://slack.com/ "link to slack site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/slack.png" %}

Chat for teams, with GitHub and Google hangouts integration. (For hangouts, just type /hangout in any channel.) “Slack is a platform for team communication: everything in one place, instantly searchable, available wherever you go.”


### [PrettyDiff](http://prettydiff.com/ "link to prettydiff site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/prettydiff.png" %}

“This tool was originally created to compare minified code by attaching a beautifier and minifier to a file comparison tool. Over the years it has grown into custom language parsers capable of performing a variety of language analysis. This application is 100% vanilla JavaScript and is API independent.”<br />
_3&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;277 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;31_


### [ES6 Fiddle](http://www.es6fiddle.net/ "link to es6fiddle site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/es6fiddle.png" %}

“Fiddlin’ with ECMAScript6.” Includes sample code illustrating these ES6 aspects: arrow functions, block scope, classes and inheritance, default parameters, destructured assignment, generators, iterators, map, promises, rest parameters, set, spread operator and template literals.<br />
_A project of Jeff McRiffey. 2&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;31 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;5_







<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="building"></a>Building

###[Browserify](http://browserify.org/ "link to browserify.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/browserify.png" %}

Bundle modules for the browser. “browserify is a tool for compiling node-flavored commonjs modules for the browser.

“You can use browserify to organize your code and use third-party libraries even if you don’t use node itself in any other capacity except for bundling and installing packages with npm.

“The module system that browserify uses is the same as node, so packages published to npm that were originally intended for use in node but not browsers will work just fine in the browser too.

“Increasingly, people are publishing modules to npm which are intentionally designed to work in both node and in the browser using browserify and many packages on npm are intended for use in just the browser. [npm is for all javascript](http://maxogden.com/node-packaged-modules.html "link to post on using npm for client-side programs"), front or backend alike.” <br />
_Project of James Halliday. 134 contributors <span class="octicon octicon-star"></span>star:&nbsp;6,520 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;582_


###[How to use NPM as a Build Tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/ "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/use-npm-as-a-build-tool.png" %}

“npm has a great subset of functionality dedicated to running tasks to facilitate in a packages lifecycle — in other words, it is a great tool for build scripts.” <br />
_By Keith Cirkel. Posted on December 9, 2014_


<!--  ===============================================================================  -->

### <a name="testing-lint-quality-checkers"></a>Testing / Lint / Quality checkers

### [JSHint](http://jshint.com/ "link to jshint.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/jshint.png" %}

“JSHint scans a program written in JavaScript and reports about commonly made mistakes and potential bugs. The potential problem could be a syntax error, a bug due to implicit type conversion, a leaking variable or something else.

“Only 15% of all programs linted on this website pass the JSHint checks. In all other cases, JSHint finds some red flags that could’ve been bugs or potential problems.” <br />
_JSHint created and maintained by Anton Kovalyov. 184 contributors <span class="octicon octicon-star"></span>star:&nbsp;4,526 <br /><span class="octicon octicon-repo-forked"></span>fork:&nbsp;951_


### [ESLint](http://eslint.org/ "link to eslint.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/eslint.png" %}

“ESLint is an open-source JavaScript linting utility.... JavaScript, being a dynamic and loosely-typed language, is especially prone to developer error. Without the benefit of a compilation process, JavaScript code is typically executed in order to find syntax or other errors. Linting tools like ESLint allow developers to discover problems with their JavaScript code without executing it.

“The primary reason ESLint was created was to allow developers to create their own linting rules. ESLint is designed to have all rules completely pluggable. The default rules are written just like any plugin rules would be. They can all follow the same pattern, both for the rules themselves as well as tests. ...

“ESLint is written using Node.js to provide a fast runtime environment and easy installation via npm.”<br />
_Created by Nicholas C. Zakas in June 2013. 127 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,572 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;265_


### [Istanbul](https://github.com/gotwarlost/istanbul "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/istanbul.png" %}

Code coverage reporting. <br />
_A project of Krishnan Anantheswaran. 36 contributors <span class="octicon octicon-star"></span>star:&nbsp;2,177 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;206_


### [tape](https://github.com/substack/tape "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/tape.png" %}

Minimal, dead simple unit testing. (This is all you need, really!) Tape is a “tap-producing test harness for node and browsers.” <br />
_A project of James Halliday. 24 contributors <span class="octicon octicon-star"></span>star:&nbsp;533 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;62_


### [faucet](https://github.com/substack/faucet "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/faucet.png" %}

Prettify unit testing output (like what comes from tape). Faucet is a “human-readable TAP summarizer” <br />
_A project of James Halliday. 2 contributors <span class="octicon octicon-star"></span>star:&nbsp;180 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;3_


### [Supertest](https://github.com/tj/supertest "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/supertest.png" %}

The best way to test HTTP endpoints: “Super-agent driven library for testing node.js HTTP servers using a fluent API.

“The motivation with this module is to provide a high-level abstraction for testing HTTP, while still allowing you to drop down to the lower-level API provided by super-agent.”<br />
_Project maintained by Visionmedia. 30 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,730 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;136_





<!--  ===============================================================================  -->

### <a name="transpilers"></a>Transpilers

### [Babel](https://github.com/babel/babel "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/babel.png" %}

Transpile ES6, ES7 to ES5: “Babel is a transpiler for writing next-generation JavaScript. (Previously 6to5)” (link to [babeljs.io](http://babeljs.io "link to babeljs.io site"))<br />
_50 contributors <span class="octicon octicon-star"></span>star:&nbsp;3,430 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;127_


### [CoffeeScript](http://coffeescript.org/ "link to coffeescript site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/coffeescript.png" %}

“CoffeeScript is a little language that compiles into JavaScript. Underneath that awkward Java-esque patina, JavaScript has always had a gorgeous heart. CoffeeScript is an attempt to expose the good parts of JavaScript in a simple way.

“The golden rule of CoffeeScript is: ‘It’s just JavaScript.’ The code compiles one-to-one into the equivalent JS, and there is no interpretation at runtime. You can use any existing JavaScript library seamlessly from CoffeeScript (and vice-versa). The compiled output is readable and pretty-printed, will work in every JavaScript runtime, and tends to run as fast or faster than the equivalent handwritten JavaScript.”<br />
_A project of Jeremy Ashkenas. 169 contributors <span class="octicon octicon-star"></span>star:&nbsp;10,686 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;1,401_


### [Emscripten](http://kripken.github.io/emscripten-site/ "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/emscripten.png" %}

Frequently used for C/C++ JavaScript ports: “Practically any portable C or C++ codebase can be compiled into JavaScript using Emscripten, ranging from high-performance games that need to render graphics, play sounds, and load and process files, through to application frameworks like Qt.” <br />
_A project of Alon Zakai. 161 contributors <span class="octicon octicon-star"></span>star:&nbsp;7,816 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;865_


### [ES6 tools](https://github.com/addyosmani/es6-tools "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/es6-tools.png" %}

ES6 Tools list (113 listed in February 2015). (See [annotated version](http://www.super-script.us/2015/es6-tools.html "link to annotated version here at super-script.us")) <br />
_A project of Addy Osmani. 27 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,510 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;81_







<!--  ===============================================================================  -->
<!--  ===============================================================================  -->


## <a name="javascript-environments"></a>JavaScript environments

### [Node](http://nodejs.org/ "link to nodejs.org website")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nodejs-org.png" %}

Server-side JavaScript and more <br />
_585&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;34,655 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;7,718_



### [io.js](https://iojs.org/ "link to iojs.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/io-js.png" %}

The Node fork.

“io.js is a JavaScript platform built on [Chrome’s V8 runtime](http://code.google.com/p/v8/ "link to V8 site"). This project began as a fork of [Joyent’s Node.js™](https://nodejs.org/ "link to nodejs.org") and is compatible with the [npm](https://www.npmjs.org/ "link to npmjs.org") ecosystem.

“Why? io.js aims to provide faster and predictable release cycles. It currently merges in the latest language, API and performance improvements to V8 while also updating libuv and other base libraries.

“This project aims to continue development of io.js under an ‘[open governance model](https://github.com/iojs/io.js/blob/v1.x/GOVERNANCE.md#readme "link to io.js project governance document")’ as opposed to corporate stewardship.”<br />
_632 contributors <span class="octicon octicon-star"></span>star:&nbsp;9,880 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;599_






<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="libraries"></a>Libraries

### [es5-shim](https://github.com/es-shims/es5-shim "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/es5-shim.png" %}

“es5-shim.js and es5-shim.min.js monkey-patch a JavaScript context to contain all EcmaScript 5 methods that can be faithfully emulated with a legacy JavaScript engine.” Stable, production ready. <br />
_55 contributors <span class="octicon octicon-star"></span>star:&nbsp;3,430 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;477_


### [es6-shim](https://github.com/es-shims/es6-shim/ "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/es6-shim.png" %}

“Provides compatibility shims so that legacy JavaScript engines behave as closely as possible to ECMAScript 6 (Harmony).” Somewhat stable, but a few things I thought were solid got shifted to ES7. <br />
_30 contributors <span class="octicon octicon-star"></span>star:&nbsp;43 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;78_


### [es7-shim](https://www.npmjs.com/package/es7-shim "link to package site at npm")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/es7-shim.png" %}

“es7-shim.js exports an object that contains shims that can be used to monkeypatch a JavaScript context to contain all ECMAScript 7 methods that can be faithfully emulated with a legacy JavaScript engine.” Experimental. Use with caution.


### [HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills "link to Modernizr GitHub wiki page on HTML5 cross-browser polyfills")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/html5-cross-browser-polyfills.png" %}

A fairly comprehensive list of HTML5 API polyfills. <br />
_311 items arranged by 69 main categories_


### [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/html5-boilerplate.png" %}

For educational use only. You’ll want to cherry-pick the best of this for your production apps.  See [Initializr](http://www.initializr.com): “A professional front-end template for building fast, robust, and adaptable web apps or sites.”<br />
_A project of [H5BP](https://github.com/h5bp "link to GitHub site") maintained by Mathias Bynens and Hans Christian Reinl. <br />
190 contributors <span class="octicon octicon-star"></span>star:&nbsp;28,665 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;7,409_


### [The Isomorphic Express Boilerplate](https://github.com/ericelliott/isomorphic-express-boilerplate "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/isomorphic-express-boilerplate.png" %}

Write apps using the same code for both the client and the server using Node, Express, and Browserify: “Isomorphic means that it’s designed to run a lot of the same code on both the client and the server. There are many advantages to building apps this way, but the primary advantages are:

- “Cross-functional teams. Since everything is written in JavaScript, it’s easier to build teams who know how to work on both the client and server sides of the app.

- “Write once, run everywhere. With the exception of a few library substitutions and browser polyfills, the code is shared, which means you have to write about half the code you’d write working on a non-isomorphic app.

- “More productive developers. Since the app is more consistent across the stack, there’s no context switching when you need to maintain application behavior on both sides of the stack. Write the behavior once, and you’re done.”

_A project of Eric Elliott. 2 contributors <span class="octicon octicon-star"></span>star:&nbsp;17 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;3_


### [rootrequire](https://github.com/ericelliott/rootrequire "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/rootrequire.png" %}

Require files relative to your project path using the normal node <code>require()</code>.

“Why?

- “You can move files around more easily than you can with relative paths like <code>../../lib/my-lib.js</code>

- “Every file documents your app’s directory structure for you. You’ll know exactly where to look for things.

- “Dazzle your coworkers.”<br />
_A project of Eric Elliott. <span class="octicon octicon-star"></span>star:&nbsp;3_


### [native-promise-only](https://github.com/getify/native-promise-only "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/native-promise-only.png" %}

An ECMAScript-standard promise polyfill by <i>Kyle Simpson</i>. “The aim of this project is to be the smallest polyfill for Promises, staying as close as possible to what’s specified in both Promises/A+ and the upcoming ES6 specification.”<br />
_A project of Kyle Simpson. 2 contributors <span class="octicon octicon-star"></span>star:&nbsp;262 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;16_


### [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/isomorphic-fetch.png" %}

A <a href="https://fetch.spec.whatwg.org/" rel="noreferrer">WHATWG fetch</a> standard polyfill <br />
_By Matt Andrews. 3 contributors <span class="octicon octicon-star"></span>star:&nbsp;38 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;3_


### [sseasy](https://github.com/heroku/sseasy "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/sseasy.png" %}

Server Sent Events for Node (HTML5 standard push notifications). “Server-sent events middleware for [Connect](https://github.com/senchalabs/connect "link to Connect, a middleware layer for Node") & [Express](http://expressjs.com/ "link to expressjs site").

“All messages in a single connection are sent with incrementing IDs. If the client passes an ID in a <code>last-event-id</code> header, the middleware ignores messages until that ID is reached.”<br />
_A project of Heroku. <span class="octicon octicon-star"></span>star:&nbsp;4 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;1_


### [EventSource browser Polyfill](https://github.com/Yaffle/EventSource/ "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/eventsource-polyfill.png" %}

Required client-side patching to support Server Sent Events. “A polyfill for http://www.w3.org/TR/eventsource/”<br />
_A project of Yaffle. 6 contributors <span class="octicon octicon-star"></span>star:&nbsp;562 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;80_


### [jQuery](http://jquery.com/ "link to jQuery site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/jquery.png" %}

Yes, I [still use jQuery](https://docs.google.com/document/d/1LPaPA30bLUB_publLIMF0RlhdnPx_ePXm7oW02iiT6o/ "link to post") and so do 61% of the top 100,000 websites — for good reason.<br />
_213 contributors <span class="octicon octicon-star"></span>star:&nbsp;33,341 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;7,946_


### [Blaze](http://meteor.github.io/blaze/ "link to Blaze website")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/blaze.png" %}

DOM-diffing isomorphic reactive templates from Meteor. “HTML templating is central to web applications. With Blaze, Meteor’s live page update technology, you can render your HTML reactively, meaning that it will update automatically to track changes in the data used to generate it.”<br />
_2 contributors <span class="octicon octicon-star"></span>star:&nbsp;74 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;8_


### [RxJS](https://github.com/Reactive-Extensions/RxJS "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/reactive.png" %}

Reactive extensions for JavaScript. [What’s reactive?](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4 "link to article, 'The two pillars of JS' ") <br />
_93 contributors <span class="octicon octicon-star"></span>star:&nbsp;3,077 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;287_


### [Page.js](https://github.com/visionmedia/page.js "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/visionmedia-page-js.png" %}

Tiny client-side router, inspired by Express: “~1200 bytes.”<br />
_Project maintained by Visionmedia. 42 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,903 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;197_


### [Moment](http://momentjs.com "link to momentjs.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/moment.png" %}

A lightweight JavaScript date library for parsing, validating, manipulating, and formatting dates. Includes 81 locale/script/language combinations. “Moment was designed to work both in the browser and in Node.JS. All code will work in both environments. All unit tests are run in both environments.” <br />
_233 contributors <span class="octicon octicon-star"></span>star:&nbsp;19,565 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;2,047_


### [Globalize](https://github.com/jquery/globalize "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/globalize.png" %}

i18n / translate your app for many languages and locations (locales). “Each language, and the countries that speak that language, have different expectations when it comes to how numbers (including currency and percentages) and dates should appear. Obviously, each language has different names for the days of the week and the months of the year. But they also have different expectations for the structure of dates, such as what order the day, month and year are in. In number formatting, not only does the character used to delineate number groupings and the decimal portion differ, but the placement of those characters differ as well.

“A user using an application should be able to read and write dates and numbers in the format they are accustomed to. This library makes this possible, providing an API to convert user-entered number and date strings — in their own format — into actual numbers and dates, and conversely, to format numbers and dates into that string format.” <br />
_26 contributors <span class="octicon octicon-star"></span>star:&nbsp;1,497 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;335_


### [Express](http://expressjs.com/ "link to expressjs.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/express.png" %}

The most popular framework for Node. “A fast, un-opinionated, minimalist web framework for Node.js applications.” <br />
_168 contributors <span class="octicon octicon-star"></span>star:&nbsp;17,445 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;3,580_


### [Stampit](https://github.com/ericelliott/stampit "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/stampit.png" %}

Stampit — create objects from reusable, composable behaviors. Prototypal inheritance with stamps. <br />
_A project of Eric Elliott. 9 contributors <span class="octicon octicon-star"></span>star:&nbsp;665 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;38_


### [Credential](https://github.com/ericelliott/credential "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/credential.png" %}

If you write Node apps with password logins, you need Credential: “Easy password hashing and verification in Node. Protects against brute force, rainbow tables, and timing attacks.”<br />
_A project of Eric Elliott. 6&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;138 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;8_


### [cuid](https://github.com/ericelliott/cuid "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/cuid.png" %}

GUIDs are broken — use cuid, instead. “Collision-resistant ids optimized for horizontal scaling and performance.”<br />
_A project of Eric Elliott. 4&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;221 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;8_


### [Velocity](http://julian.com/research/velocity/ "link to Velocity site")
 &amp; [Velocity Motion Designer (VMD)](ttp://julian.com/research/velocity/#vmd "link to VMD section")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/velocity.png" %}

UI animation library: “Velocity is an animation engine with the same API as jQuery’s <code>$.animate()</code>. It works with and without jQuery. It’s incredibly fast, and it features color animation, transforms, loops, easings, SVG support, and scrolling. It is the best of jQuery and CSS transitions combined.”<br />
_A project of Julian Shapiro. 14&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;6,725 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;520_


### [json-schema](https://github.com/kriszyp/json-schema "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/json-schema.png" %}

Great for model validations: “JSON Schema describes your JSON data format.”<br />
_12&nbsp;contributors (at github.com/json-schema)<span class="octicon octicon-star"></span>star:&nbsp;453 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;97_








<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="web-components"></a>Web Components


### [FIRST](http://addyosmani.com/first/ "link to post")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/first.png" %}

“**Components Should Be Focused, Independent, Reusable, Small &amp; Testable (FIRST)**

“Whether it’s a client- or server-side component, a Node module or a piece of visual UI, components that are [large](http://addyosmani.com/largescalejavascript/ link to 'Patterns For Large-Scale JavaScript Application Architecture' ") are inherently more complex to maintain than those than are small.

“In fact, the _secret_ to efficiently building ‘large’ things is generally to avoid building them in the first place. Instead, compose your large thing out of **smaller**, more **focused** pieces. This makes it easier to see how the small thing fits within the broader scope of your large thing.” <br />
_By Addy Osmani. Posted circa May 9, 2014_


### [Polyfills](http://webcomponents.org/polyfills/ "link to webcomponents.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/polyfills.png" %}

“<code>webcomponents.js</code> is a set of polyfills built on top of the **Web Components** specifications. It makes it possible for developers to use these standards today across all modern browsers.

“As these technologies are implemented in browsers, the polyfills will shrink and you’ll gain the benefits of native implementations. <code>webcomponents.js</code> automatically detects native support and switches to the fast path when available. Your elements seamlessly start relying on the native stuff — and get faster in the process.

“**Note:** The <code>webcomponents.js</code> polyfill layer is no longer needed for browsers that fully implement the Web Components APIs, such as Chrome 36+.”<br />
_24&nbsp;contributors (at github.com/webcomponents/webcomponentsjs)<span class="octicon octicon-star"></span>star:&nbsp;371 <br /><span class="octicon octicon-repo-forked"></span>fork:&nbsp;65_


### [HTML Imports](http://webcomponents.org/articles/introduction-to-html-imports/ "link to article at webcomponents.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/html-imports.png" %}

“Template, Shadow DOM, and Custom Elements enable you to build UI components easier than before. But it’s not efficient to load each resources such as HTML, CSS and JavaScript separately.

“Deduping dependencies isn’t easy either. To load a library like jQuery UI or Bootstrap today requires using separate tags for JavaScript, CSS, and Web Fonts. Things get even more complex if you deal with Web Components with multiple dependencies.

“HTML Imports allow you to load those resources as an aggregated HTML file.”<br />
_By Eiji Kitamura. Includes 8:12 video. Published at webcomponents.org on January 4, 2015_


### [Custom Elements](http://webcomponents.org/articles/introduction-to-custom-elements/ "link to article at webcomponents.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/custom-elements.png" %}

“HTML is the most important factor for the web platform. It provides various low level features to structure sites and apps. But it also is easy to end up with div soup once you start implementing a complex component using native HTML tags. What if the web platform could allow you to create your original component? What if you can give it an arbitrary tag name? What if you can extend features of an existing HTML tag? Custom Elements allow you to do those things.”
<br />
_By Eiji Kitamura. Includes 8:16 video. Published at webcomponents.org on November&nbsp;23, 2014_


### [Templates](http://webcomponents.org/articles/introduction-to-template-element/ "link to article at webcomponents.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/templates.png" %}

“‘Templates’ used to be a technology frequently used with server-side technologies such as PHP, Django (Python) or Ruby on Rails. But lately it’s becoming more common to use templates in the browser.

“This is primarily driven by the changing landscape of web architecture. Servers are becoming more dedicated to processing data, clients are becoming more dedicated to user interactions and views. MVC (Model, View, Controller) is no longer a server-side-only pattern, it’s becoming a client-side thing — look at AngularJS, Backbone.js, Ember.js, etc.
<br />_By Eiji Kitamura. Includes 4:02 video. Published at webcomponents.org on October 6, 2014_


### [Shadow DOM](http://webcomponents.org/articles/introduction-to-shadow-dom/ "link to article at webcomponents.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/shadow-dom.png" %}

“An element that has a shadow root associated with it is called ‘shadow host.’ The shadow root can be treated as an ordinary DOM element so you can append arbitrary nodes to it.

“With Shadow DOM, all markup and CSS are scoped to the host element. In other words, CSS styles defined inside a Shadow Root won’t affect its parent document; CSS styles defined outside the Shadow Root won’t affect the main page.”
<br />_By Eiji Kitamura. Includes 5:18 video. Published at webcomponents.org on October 29, 2014_


### [x-gif](http://geelen.github.io/x-gif/#/http://i.imgur.com/iKXH4E2.gif "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/x-gif.png" %}

This web component wins the internet: “<code>&lt;x-gif></code> is a web component for flexible GIF playback. Speed them up, slow them down, play them in reverse, synch multiple beats to a rhythm, synch them to audio, whatever you like.”<br />
_A project of Glen Maddern. 4&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;1,522 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;72_


### [Vulcanize](https://github.com/Polymer/vulcanize "link to GitHub page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/vulcanize.png" %}

Don't let web components slow your app down. Bundle your HTML imports: “Build tool for HTMLImports and Web Components. Named for the Vulcanization process that turns polymers into more durable materials.”<br />
_12&nbsp;contributors<span class="octicon octicon-star"></span>star:&nbsp;566 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;51_





<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="qa-deployment-monitoring-ci"></a>QA / Deployment / Monitoring / CI


### [PM2](https://github.com/Unitech/pm2 "link to GitHub site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/pm2.png" %}

Process monitoring / self repair: “PM2 is a production process manager for Node.js applications with a built-in load balancer. Perfectly designed for microservice architecture. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.”<br />
_A project of Alexandre Strzelewicz. 74&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;6,364 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;472_


### [New Relic](http://newrelic.com/ "link to New Relic site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/new-relic.png" %}

Deep insights into the performance and health of your production apps: “What is software analytics?
It’s about gaining actionable, real-time business insights from the billions of metrics your software is producing, including user click streams, mobile activity, end user experiences and transactions.”


### [Sauce Labs](https://saucelabs.com/ "link to saucelabs.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/sauce-labs.png" %}

Cross-platform web application testing with great collaboration and integration support.


### [Travis CI](https://travis-ci.org/ "link to travis-ci.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/travis-ci.png" %}

CI, of course: “Travis CI is a hosted continuous integration service. It is integrated with GitHub and offers first-class support for C, C++, Clojure, C#, D, Dart, Erlang, F#, Go, Groovy, Haskell, Java, JavaScript (with Node.js), Julia, Objective-C, Perl, PHP, Python, Ruby, Rust, Scala, Visual Basic <br/>

“Travis CI’s build environment provides different runtimes for different languages, for instance multiple versions of Ruby, PHP, Node.js. It also comes preinstalled with a variety of data stores and common tools like message brokers.<br />

“Continuous deployment to the following providers are currently supported out of the box — Appfog, biicode, Cloud 66, Heroku, AWS CodeDeploy, Modulus, Nodejitsu, OpenShift, cloudControl, CloudFoundry, RubyGems, AWS OpsWorks, PyPI, Divshot.io, Rackspace Cloud Files, npm, S3, Ninefold, Engine Yard, GitHub Releases, Deis, Hackage, Google Cloud Storage, packagecloud.io”


### [Docker](https://www.docker.com/ "link to docker.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/docker.png" %}

Run your CI process using the same OS configs as your production systems.<br />

“Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications. Consisting of Docker Engine, a portable, lightweight runtime and packaging tool, and Docker Hub, a cloud service for sharing applications and automating workflows, Docker enables apps to be quickly assembled from components and eliminates the friction between development, QA, and production environments.”
<br />
_765&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;19,118 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;3,946_


### [Shippable](https://www.shippable.com/ "link to shippable.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/shippable.png" %}

Docker-based hosted build / CI.

“Chris Corriveau, CTO, StockTwits: ‘If your goal is to commit code often, test it, and ship to production as fast as possible to keep up with your companies changing features and initiatives there is no better product than Shippable! Using Shippable cut down our testing time from over 20 mins to under 8 mins.’ ”








<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="community"></a>Community

<!--
### [ES Discuss](https://esdiscuss.org/ "link to esdiscuss.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/esdiscuss.png" %}

The mailing list where all the ECMAScript standard discussion action is.<br />

Notably (as the GitHub site puts it), “esdiscuss.org aims to produce a readable copy of the [esdiscuss mailing list archives](https://mail.mozilla.org/pipermail/es-discuss/ "link to es-discuss at mozilla.org").
-->


### [JavaScript on Google+](https://plus.google.com/communities/100875929141897651837 "link to JavaScript community on Google+")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/js-on-google-plus.png" %}


_106,012 members. You can view pages or posts in areas identified as “questions, beginners, discussion, ‘show your work,’ MV* frameworks, libraries, guides/tutorials, books, widgets (jQuery, etc) and videos,” as well as shared photos and off-topic items._


### [HTML5 on Google+](https://plus.google.com/communities/103299867207875326585 "link to html5 community on Google+")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/html5-on-google-plus.png" %}

“A community for html5-related stuff. Links from all around the web, new spec announcements, cool new stuff and other things.<br />

“We talk about: HTML, CSS, CSS3, JS, JavaScript, web development, front end, open source, webGL, Google chrome extensions, browsers, Mozilla Firefox, Internet Explorer, Safari, Opera, development, code, coffeescript, responsive design, web tools, web applications, w3c standards, and other cool stuff.”<br />
_219,283 members_


### [Node.js on Google+](https://plus.google.com/communities/115365528781941125390 "link to node.js community on Google+")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/node-on-google-plus.png" %}

_50,558 members. You can view pages or posts in areas identified as “discussion, question, libraries &amp; frameworks, tutorials &amp; books and showcase,” as well as shared photos._


### IRC ##JavaScript

irc://irc.freenode.net/javascript


### IRC #node.js

irc://irc.freenode.net/node.js


### IRC #io.js

irc://irc.freenode.net/io.js — the Node fork








<!--  ===============================================================================  -->
<!--  ===============================================================================  -->

## <a name="news"></a>News


### [JavaScript Weekly](http://javascriptweekly.com/ "link to javascriptweekly site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/javascriptweekly.png" %}

“A free, once–weekly e-mail round-up of JavaScript news and articles.

“ONE e-mail each Friday.”<br />
_Published by [Cooper Press](https://cooperpress.com/ "link to Cooper Press") and curated by [Peter Cooper](http://twitter.com/peterc "link to @peterc Twitter page")_


### [Node Weekly](http://nodeweekly.com/ "link to nodeweekly site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nodeweekly.png" %}

“A free, once–weekly e-mail round-up of Node.js news and articles.

“ONE e-mail each Wednesday.”<br />
_Published by [Cooper Press](https://cooperpress.com/ "link to Cooper Press")_


### [HTML5 Weekly](http://html5weekly.com/ "link to html5weekly site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/html5weekly.png" %}

“A once–weekly HTML5 and Web Platform technology roundup. CSS 3, Canvas, WebSockets, WebGL, Native Client, and more.

“ONE e-mail each Wednesday.”<br />
_Published by [Cooper Press](https://cooperpress.com/ "link to Cooper Press") and curated by [Peter Cooper](http://twitter.com/peterc "link to @peterc Twitter page")_


### [EchoJS](http://www.echojs.com/ "link to echojssite")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/echojs.png" %}

“Echo JS is a community-driven news site entirely focused on JavaScript development, HTML5, and front-end news.”<br />
_Founder and maintainer: Frederic Cambus, advisor: Fabien Allanic_


### [DailyJS](http://dailyjs.com/ "link to dailyjssite")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/dailyjs.png" %}

Daily round-ups, dating back to November 2009.<br />
_Editor-in-chief: [Alex R. Young](http://twitter.com/#!/alex_young "link to @alex_young Twitter page"), proofreader: [Yuka Young](http://twitter.com/#!/YukaYoung "link to @YukaYoung Twitter page")_


### [JavaScript Jabber](http://devchat.tv/js-jabber/ "link to JavaScript Jabber site")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/js-jabber.png" %}

Weekly podcast.<br />
_Moderated by Charles Max Wood, with regular panel members and a weekly guest_








<!--  ===============================================================================  -->
<!--  ===============================================================================  -->
## <a name="pasting-sharing-code"></a>Pasting / sharing code


### [Codepen](http://codepen.io/pen/ "link to codepen.io")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/codepen.png" %}

“CodePen is for web designers and front-end developers.

“It is an HTML, CSS, and JavaScript code editor in your browser with instant previews of the code you see and write. It is a searchable trove of your own creations, and a world of other people’s creations. A place to troubleshoot, to teach, to learn, to test, and to grow.”


### [RequireBin](http://requirebin.com/ "link to requirebin.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/requirebin-demo.png" %}

“Shareable JavaScript programs powered by NPM and browserify” (e.g., you can require npm modules from the browser via browserify and browserify-cdn).








<!--  ===============================================================================  -->
<!--  ===============================================================================  -->
## <a name="contests"></a>Contests


### [DemoJS](http://demojs.org/ "link to demojs.org")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/demojs.png" %}

The JavaScript demoscene party: “DemoJS is a day-long, open-to-all, web-based, but not only, free [demoparty](http://en.wikipedia.org/wiki/Demoparty "link to Wikipedia entry for demoparty")


### [JS1k](http://js1k.com/ "link to js1k.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/js1k.png" %}

JavaScript demos in 1k of memory: JS1K “runs yearly, usually in or around February / March. The core rule is no externals. You must submit a self-contained demo in 1024 bytes of pure JS, which in turn may use various web technologies.”<br />
_Created and  maintained by Peter van der Zee_


### [JS13k Games](http://js13kgames.com/ "link to js13kgames.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/js13kgames.png" %}

JavaScript games in 13k of memory: “Js13kGames is a JavaScript coding competition for HTML5 game developers. The fun part of the compo is the file size limit set to 13 kilobytes.”<br />
_Organized by [Andrzej Mazur](https://twitter.com/end3r "link to @end3r Twitter page")_


### [FightCode game](http://fightcodegame.com/ "link to fightcodegame.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/fightcodegame.png" %}

Program virtual battle bots and climb the leaderboard: “fightcodegame.com is a free-to-play game and you can create as many robots as you’d like.
<br />
“Coding your robots is very easy and should be natural if you’ve ever had any JavaScript experience.”<br />
_“Battle against 26,782 other robots”_


### [Node Knockout](http://nodeknockout.com/ "link to nodeknockout.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nodeknockout.png" %}

The legendary Node competition: “Node Knockout is the world’s biggest Node.js programming competition — a 48-hour coding contest featuring node.js”

In 2014, contestants could compete ‘virtually’ from anywhere in the world, with Knockout HQ located in San Francisco and competition sites in Chicago, Tokyo, Venice, Taipei and Reno, Nevada.







<!--  ===============================================================================  -->
<!--  ===============================================================================  -->
## <a name="hackable-hardware"></a>Hackable Hardware


### [Nodebots](http://nodebots.io/ "link to nodebots.io")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nodebots.png" %}

“Robots powered by JavaScript.<br />

“That’s right... if you’ve any JavaScript experience, you can now use your powers to manipulate the machines. From [blinking lights](http://instagram.com/p/cFVNtmJxlc/ "link to video on Instagram") to [Sumo Bot battles](http://nodebots.io/sumo.html "link to Sumo competition rules"), [remote-control cats](http://www.youtube.com/watch?v=6NYyGC-wZKU "link to video on YouTube"), and [bull fighting with quadcopters](https://github.com/substack/matador-copter "code for the Parrot AR Quadricopter")....”


### [Cylon](http://cylonjs.com/ "link to cylonjs.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/cylonjs.png" %}

“Cylon.js is a JavaScript framework for robotics, physical computing, and the Internet of Things. It makes it incredibly easy to command robots and devices.”


### [Nodecopter](http://www.nodecopter.com/ "link to nodecopter.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/nodecopter.png" %}

“NodeCopter.js is a fullday event where 15–60 developers team up in groups of 3.

“Each team receives one Parrot AR Drone 2.0 and spends the day programming and playing with it. At the end of the day, each team gets to present their work to the other attendees.”


### [Tessel](https://tessel.io/ "link to tessel.io")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/tessel.png" %}

“Tessel is a microcontroller that runs JavaScript. It’s Node-compatible and ships with Wifi built in. Use it to easily make physical devices that connect to the web.

“Tessel runs JavaScript — no server necessary. Just like web or mobile development, use your own IDE and libraries to program physical applications. Tessel supports packages from npm — that’s HTTP, Twitter, web server, color, and async support right out of the box.”


### [Espruino](http://www.espruino.com/ "link to espruino.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/espruino.png" %}

“While Tessel and Espruino both run JavaScript, they’re very different. Tessel is aimed at internet-connected devices (it’s more like a Raspberry Pi), and Espruino is aimed at low-power devices (more like an Arduino).

“The two areas overlap a lot, but the main differences are: Espruino is a lot cheaper (1/3 of the price), Tessel has more memory, Espruino uses a lot less power so it can run for years on a battery, Tessel is faster, Tessel has WiFi built in (but you can plug WiFi or Ethernet modules into Espruino), and Tessel provides pre-made modules that can be plugged in for certain things — Espruino’s emphasis is on using standard hardware that’s available cheaply from a variety of vendors.”







<!--  ===============================================================================  -->
<!--  ===============================================================================  -->
## <a name="hosting"></a>Hosting


### [DigitalOcean](https://www.digitalocean.com/?refcode=fdcfedac5208 "link to digitalocean.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/digitalocean.png" %}

“DigitalOcean is a platform created for developers who need to launch and scale their applications quickly. Additionally, DigitalOcean provides the perfect environment for developers to play around on the command line and learn more about customizing their own servers.

“DigitalOcean is a simple and fast cloud hosting provider built for developers. Customers can create a cloud server in 55 seconds, and pricing plans start at only $5 per month for 512MB of RAM, 20GB SSD, 1 CPU, and 1TB Transfer.”







<!--  ===============================================================================  -->
<!--  ===============================================================================  -->
## <a name="for-kids"></a>For kids (and people who just love to have fun)

### [JavaScript for Kids](http://www.amazon.com/gp/product/B00QL616QE?ie=UTF8&camp=213733&creative=393177&creativeASIN=B00QL616QE&linkCode=shr&tag=ericleads-20&linkId=6AOODC27L6URY3K2 "link to Amazon page for this book")

See [information](#javascript-for-kids) above in [Books](#books) section.


### [LearnToMod](http://www.learntomod.com/ "link to learntomod.com")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/learntomod.png" %}

Mod Minecraft with JavaScript: “LearnToMod lets you mod Minecraft with either JavaScript or Blockly — or even a combination of the two. Blockly is accessible to children as young as 8. And JavaScript can be challenging to coders of any age.

“Blockly is a great way to learn deep computer science concepts like if-statements, loops, data types, boolean logic, object-oriented programming, event-driven programming, and more. Once you’ve learned these concepts in Blockly, the only hurdle that remains is to learn the syntax of JavaScript. This is much easier than trying to learn these concepts and the syntax of JavaScript simultaneously.”


### [The Young Person’s Guide to Programming in Minecraft](https://github.com/walterhiggins/ScriptCraft/blob/master/docs/YoungPersonsGuideToProgrammingMinecraft.md#the-young-persons-guide-to-programming-in-minecraft "link to GitHub page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/ypguide.png" %}

“I created ScriptCraft to make it easier for younger programmers to
create their own Minecraft Mods. Mods are written using the
Javascript programming language. Once the ScriptCraft mod is
installed, you can add your own new Mods by adding Javascript (.js)
files in a directory.”<br />
_A project of Walter Higgins. 24&nbsp;contributors <span class="octicon octicon-star"></span>star:&nbsp;532 <span class="octicon octicon-repo-forked"></span>fork:&nbsp;85_


<!-- 
 * “If you're new to programming and want to start modding Minecraft, then [Start Here](https://github.com/walterhiggins/ScriptCraft/blob/master/docs/YoungPersonsGuideToProgrammingMinecraft.md "link to docs").
 * “If you've already used [Scratch](http://scratch.mit.edu/ "link to scratch.mit.edu"), have attended a few [CoderDojo](http://coderdojo.com/ "link to coderdojo.com") sessions, or have already dabbled with Javascript, then [Start Here][http://cdathenry.wordpress.com/category/modderdojo/].
 * “Watch some [demos](http://www.youtube.com/watch?v=DDp20SKm43Y&list=PL4Tw0AgXQZH5BiFHqD2hXyXQi0-qFbGp_ "link to YouTube") of what you can do with ScriptCraft.”
-->



<!--  ===============================================================================  -->
<!--  ===============================================================================  -->
## <a name="twitter"></a>Twitter (alphabetical order)


### [Addy Osmani](https://twitter.com/addyosmani "link to @addyosmani twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-addyosmani.png" %}

App architecture expert, Chrome dev tools champion

@addyosmani: “Engineer at Google working on Chrome, Web &amp; Polymer • Author • Creator of TodoMVC, @Yeoman, Web Starter Kit, grunt-uncss &amp; others • Passionate about web tooling”<br />
_Tweets: 11.6K, followers: 90.1K_


### [Angus Croll](https://twitter.com/angustweets "link to @angustweets twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-angustweets.png" %}

Author, _If Hemingway Wrote JavaScript_

@angustweets: “Literature, JavaScript, Literary JavaScript... Author of IF HEMINGWAY WROTE JAVASCRIPT”<br />
_Tweets: 4,652, followers: 12K_


### [Axel Rauschmayer](https://twitter.com/rauschma "link to @rauschma twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-rauschma.png" %}

ES Next evangelist, author

@rauschma: “JavaScript person: blogger @2ality, trainer @Ecmanauten, organizer @MunichJS. Books (free online): – ES5: http://SpeakingJS.com  – ES6: http://2ality.com/2014/08/es6-today.html”<br />
_Tweets: 14.9K, followers: 10.7K_


### [Brendan Eich](https://twitter.com/BrendanEich "link to @BrendanEich twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-BrendanEich.png" %}

Created JavaScript

@BrendanEich: “Brendan Eich invented JavaScript, co-founded http://mozilla.org , and served as CTO, SVP Eng, and CEO, Mozilla.”<br />
_Tweets: 24.7K, followers: 37K_


### [David Nolen](https://twitter.com/swannodette "link to @swannodette twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-swannodette.png" %}

Great functional programming content

@swannodette: “musician, Cognitect, Lisp, JavaScript, Kitchen Table Coders”<br />
_Tweets: 15.4K, followers: 10.5K_


### [David Herman](https://twitter.com/littlecalculist "link to @littlecalculist twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-littlecalculist.png" %}

Author, _Effective JavaScript_

@littlecalculist: “Programming language propeller-head at Mozilla Research, author of Effective JavaScript (@effectivejs).”<br />
_Tweets: 15.9K, followers: 9,884_


### [EchoJS](https://twitter.com/echojs "link to @echojs twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-echojs.png" %}

News and links

@echojs: “Community-driven news site entirely focused on JavaScript development, HTML5, and front-end news. Maintained by @fcambus.”<br />
_Tweets: 11.9K, followers: 5,468_


### [Eric Elliott](https://twitter.com/_ericelliott "link to @_ericelliott twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-_ericelliott.png" %}

That’s me. O’Reilly author. JavaScript architect. JS Instructor.

@\_ericelliott: “Compassionate entrepreneur on a mission to end homelessness. #jshomes Javascript, tech education, electronic music, photography, film, viral apps.”<br />
_Tweets: 15.8K, followers: 5K_


### [Jafar Husain](https://twitter.com/jhusain "link to @jhusain twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-jhusain.png" %}

Great talks on RxJS, ES next, etc...

@jhusain<br />
_Tweets: 436, followers: 1,687_


### [James Halliday](https://twitter.com/substack "link to @substack twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-substack.png" %}

aka Substack — author of ~one million~ Node modules you probably use.

@substack: “open source librarian”<br />
_Tweets: 7,578, followers: 13.4K_


### [James Long](https://twitter.com/jlongster "link to @jlongster twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-jlongster.png" %}

CSP, functional programming advocate, Mozilla developer

@jlongster: “Works on Firefox Developer Tools at Mozilla. javascript, node, functional. https://github.com/jlongster”<br /><br />
_Tweets: 6,324, followers: 3,386_


### [JavaScript Cheerleader](https://twitter.com/JS_Cheerleader "link to @JS_Cheerleader twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-JS_Cheerleader.png" %}

Mover &amp; shaker, JavaScript evangelist, documentary film maker

@JS_Cheerleader: “#JavaScript changed my life. I’m a huge fan. Looking for cool JS projects to tweet about. I always loved #geek guys and they never loved me back until now. Yay!”<br />
_Tweets: 1,552, followers: 926_


### [JavaScript Daily](https://twitter.com/JavaScriptDaily "link to @JavaScriptDaily twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-JavaScriptDaily.png" %}

News and links

@JavaScriptDaily: “Daily JavaScript news and links”<br />
_Tweets: 3,601, followers: 120K_


### [Jordan Harband](https://twitter.com/ljharb "link to @ljharb twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-ljharb.png" %}

Keeping us ahead of the JS curve

@ljharb: “software engineer; nerd; gamer; teacher; will try anything once; a surgeon with git rebase. @Twitter, @MobBase. Favorite punctuation: ⸮, fav scent: petrichor”<br />
_Tweets: 23.5K, followers: 2,421_


### [Kyle Simpson](https://twitter.com/getify "link to @getify twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-getify.png" %}

Author, YDKJS — O’Reilly, JS Instructor, open web evangelist

@getify: “All things JavaScript. Open Web Evangelist.” (_see also_ @ydkjs)<br />
_Tweets: 61.3K, followers: 11.8K_


### [Marijn Haverbeke](https://twitter.com/marijnjh "link to @marijnjh twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-marijnjh.png" %}

Author, _Eloquent JavaScript_

@marijnjh: “Prolific coder. Person behind CodeMirror, Eloquent JavaScript, and Tern. Free-lancer.”<br />
_Tweets: 2,897, followers: 4,046_


### [Nicholas C. Zakas](https://twitter.com/slicknet "link to @slicknet twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-slicknet.png" %}

Author, speaker

@slicknet: “Front-end guy at @BoxHQ. Author. Speaker. Philosopher. Boston ex-pat. Lyme disease warrior. Lover of the web.”<br />
_Tweets: 13.8K, followers: 28.1K_


### [Nick Morgan](https://twitter.com/skilldrick "link to @skilldrick twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-skilldrick.png" %}

Author, _JavaScript for Kids_

@skilldrick: “Recovering burrito addict”<br />
_Tweets: 24.9K, followers: 2,026_


### [Paul Irish](https://twitter.com/paul_irish "link to @paul_irish twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-paul_irish.png" %}

Developer evangelist, Chrome dev tools champion

@paul_irish: “The web is awesome • I work on developer productivity for Chrome • Chrome DevTools and front-end tooling • big fan of rye whiskey, research and whimsy”<br />
_Tweets: 22.8K, followers: 151K_


### [Reginald Braithwaite](https://twitter.com/raganwald "link to @raganwald twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-raganwald.png" %}

Author, _JavaScript Allongé_, speaker, GitHub

@raganwald: “Age and treachery will overcome youth and skill. —Fausto Coppi”<br />
_Tweets: 29.4K, followers: 10K_


### [YDKJS](https://twitter.com/ydkjs "link to @ydkjs twitter page")

{% include image-no-descrip.html url="/media/2015-02-15-essential-js-links/at-ydkjs.png" %}

_You Don’t Know JS_, O’Reilly book series by Kyle Simpson

@ydkjs (_see also_ @getify)<br />
_Tweets: 808, followers: 2,318_


<p>&nbsp;</p>
<hr />

For those who want to make use of this content, it is also published as a gist at <a href="https://gist.github.com/rsperberg/ed44613269be4b1eff79" title="link to gist">gist.github.com/rsperberg/ed44613269be4b1eff79</a>.


<p>&nbsp; </p>

<small><a href="https://www.flickr.com/photos/htakashi/5291203955/ " style="text-decoration:none;">Photo</a> of parrots by <a href="https://www.flickr.com/photos/htakashi/" title="link to Takashi Hososhima Flickr page">Takashi Hososhima</a> (<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC BY-SA 2.0</a>). The image has been cropped and flipped horizontally for presentation purposes.</small>

<!--  small><a href="https://www.flickr.com/photos/gopalarathnam_v/48653786" style="text-decoration:none;">Photo</a> by Gopal Venkatesan, <em>Parrots - Jurong Bird Park</em>, <a href="https://creativecommons.org/licenses/by/2.0/">cc by 2.0</a></small  -->

<!-- a href="https://gist.github.com/ericelliott/d576f72441fc1b27dace" title="link to Eric Elliott gist"><img width="480px" src="https://raw.githubusercontent.com/rsperberg/dev-ref/master/javascript/auxi/pix/essential/elliott-essential-js-links-gist.png" /></a  -->

<!--
{% include image.html url="media/2015-02-15-essential-js-links/cover.jpg" width="100%" description="No parrots!" %}
-->
<!-- Peter Békési 2007-0204  Attribution-NonCommercial-ShareAlike 2.0 Generic (CC BY-NC-SA 2.0) https://www.flickr.com/photos/pbekesi/392765048  -->
