#Presentation on Writing Quality JavaScript

This was built on deck.js because I saw it the other day and it looked all kinds of shiny and neat so I decided to plug it in.

I generally write a little bit each time someone sends me flying into a rage with awful code. Spooling missteaks are bound to be plentiful.

# License

##"So you want to write some quality JavaScript"

So you want to write some quality JavaScript by Brian Graham is licensed under a [Creative Commons Attribution-NonCommercial 2.5 Canada License](http://creativecommons.org/licenses/by-nc/2.5/ca/).

If you're a school professor/instructor/teacher, contact me for permission. You are, in fact, a business. You make money.

Khan accademy's cool to use or remix any of this in any way should they so wish.

##Deck.js

I built this on a project called Deck.js. You can find it on GitHub.

Copyright (c) 2011 Caleb Troughton

Dual licensed under the [MIT license](https://github.com/imakewebthings/deck.js/blob/master/MIT-license.txt) and [GPL license](https://github.com/imakewebthings/deck.js/blob/master/GPL-license.txt).

# Roadmap/Goals

##Goals to resolve

- There is an issue best described as "the blind leading the blind," where many JavaScript authors feel it's fine to write some of the worst code on the face of the earth. I would like to try and make an impact here.
- I need the work to be interesting, or these people too lazy to RTFM but not lazy enough to write code will lose interest.
- I want to create "future pull" in the work. 

Honestly, I'm kicking ideas around right now...


- General kick in the face to bad code styles:
- - In-line doesn't exist anymore, don't use it, even once.
- - javascript psudo-protocol is idiotic
- - Stop doing cut+paste+tweak


- Don't suck at:
- - Loops
- - Decision structures
- - Arrays/objects
- - Events (should I cover dom first?)
- - Prototypal objects (has own porpery and truthy things)
- - One trick pony and jQuery.
- - Pretending javascript is something it's not and bitching about it later when it turns out it isn't. 
- - Noscript? (I hate this one)
- - h4x0rz


- Good/Best practices:
- - DRY code
- - design patterns
- - Documentation
- - How to name variables
- - What the hell a function and an object is


- Knowledge you should have:
- - layers of things. Maybe an overview of the OSI and HTTP?
- - unit tests
- - SCM
- - Static code analysis tools
- - DOM
- - Explain what jQuery is, explain there's life outside of it, explain it's bad
- - jsperf?
- - Browsers, how they make it work and why you make them cry


- Community:
- - How to ask questions. How to tell if someone's smarter than you. How not to piss people off.
- - Good sites (mdc, js garden w3c ...)
- - BAD sites (lookin' at you dynamic drive, javascriptkit, and w3schools.)


##Roadmap

Introduction to who the person is, some guy at a job. Or a student. I'd like to cross the broundy here somehow.

Take them through a problem they have to solve, or multiple ones. Take them through what they did (the bad solution).

Bad thigns you do:

1. cut+paste+tweak
1. in-line styles and JS
1. Psudo-protocol
1. Abuse of arrays/objects
1. loops abuse
1. control structures (lots of ifs, no idea what switch is, or something...)
1. Events everywhere on everything all the time
1. Noscript? No service.
1. Try to write the thing like it's a class.
1. global global global
1. ignore licences/copyrights
1. jQuery all the things!!!!111
1. We don't need no stinkin' comments
1. Variables that are just a few letters, or named stupidly

Smart things you don't do:

1. No SCM
1. No docs
1. no linting
1. no design patterns
1. no peer review
1. w3fools
1. Don't bother with reading specs
1. Ask for help when you need it
1. Don't know when you need help

Bad things that happen:

1. h4x/xss
1. slow
1. crashes in some browsers, not others
1. crashes in random situations but you can't figure it out so it doesn't exist
1. Nobody wants to help you

Things you need to learn:

1. OSI/HTTP
1. DOM
1. How browsers work
1. unit tests
1. spotting good code, spotting bad code


#Story Board

##Prequil: Dante's inferno.
- Show some bad code samples, stuff that's not DRY or logically seperated, etc.
- You're always over-time, over-budget
- You're constantly fixing crashes and can't figure out the bugs because you don't see them
- You're not sure how thigns work, or even where to go to start figureing out solutions
- It's all really confusing, no time to learn
- Maintainer will be a psycopath because of you

##Act one: How things work.
- Invent the internet.
- invent HTTP
- Invent HTML
- Invent JavaScript (and explain it can be run server-side). ecmascript, livescript, mocascript, jsscript, node...
- Invent the Window API, DOM API and XHR API

##Act two: This thing's bigger than just you and me
- Invent multiple browsers, and standards.
- Problems with one browser, not in others (crashes, renders, bugs, etc)
- Hack the planet (xss)
- Programming community: Good stuff, bad stuff. How to get help, peer review, docs, 
- Write code that we can actually share. This means clean code, variable names.
- No script.
- Population of the world online, vs next 10 years.

##Act Three: How to write clean code, not a mess.
- Logical variable names
- Documentation: Comments and docs
- Design patterns, abstractions (cut+paste+tweak DIES HERE)
- Hail the DOM events, the inline script tag is dead!
- Javascript: psudeo protocol doesn't work and is dead.

##Act four: How to write code that doesn't break
- Global needs to die.
- lint
- Unit tests
- SCM
- Peer review

##Act Five: How to write JavaScript that people love
- Fast (not slow)
- Events that don't suck
- DOM editing that doesn't suck
- Works everywhere, degrades gracefully.
- Copyright and licence are important.
- JS is prototypes, not classes. Stop doing that.

##Act six: Back to basics
- You're wrong, and that's awesome, because you know something now.
- You don't always need jQuery
- You don't need cut+paste+tweak, make DRY code.
- Don't abuse arrays/object differences, learn to loop, dare to dream. old Opera/FF, old MISE, sometimes Flash, 
- How decision structures can be used to your advantage, not add complexity to your code
- RTFM... specs, docs, etc.

##Act seven: Become a Samurai, not a code ninja.
- What's a Samurai? (Teaches everywhere, makes things, learns things, and a mighty force)
- What's a ninja? (Jumps in from the darkness, flips out and kills people, disapears)
- Learn to spot the bad code and the good code, find it in your own code.
- Create something, learn something, teach something.
- Broaden your horizons
- You're still wrong, even when you do know everything. Use a proof to be correct, not your status/authority.

##Epilogue
- Not sure what to put here, I need something that fills people with a good feeling for the future of all this work.



