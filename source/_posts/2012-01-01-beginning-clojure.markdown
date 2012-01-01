---
layout: post
title: "Beginning Clojure"
date: 2012-01-01 14:02
comments: true
categories: [Clojure]
---

I am a long time fan of Lisp and Scheme, and I have been meaning to pick up [Clojure](http://clojure.org) for some time, but have been unable to find enough time to do so. Starting the new year with a set of good intentions, I thought it a suitable time to try again.

The last couple of years -- actually since 2008 or so -- I have almost exclusively developed systems using Python, which I thoroughly enjoy. I have been using Python much longer than that, since somewhere in the mid-90s, but the last four years I have been using it professionally.

I do not remember exactly when I first heard of Lisp, but it must have been sometime back in the mid-eighties. I am a mostly self-taught programmer - although I later studied for an M.Sc. in computer science -- and I remember I was immediately fascinated by some of the ideas of Lisp; code-as-data, literal symbols, and iteration, to name a few.

The first real exposure to Lisp was through ["Lisp, 2nd edition"](http://www.amazon.com/Lisp-3rd-Patrick-Winston/dp/0201083191) by Patrick H. Winston and Berthold K. P. Horn (the link is to the 3rd edition, I could not find a good reference to the 2nd edition), which I picked up in a bookstore in London around '86. A little bit later I -- as so many others -- found Scheme and  [SICP](http://mitpress.mit.edu/sicp/).

Even though I have been studying Lisp and Scheme for quite a long time, my interest in and understanding of functional programming has increased radically during the last six or seven years. During that time I have read about and played with languages such as Haskell, ML, O'Caml, Erlang, Scala, and of course Clojure. This has led to changes in how I write code, also in languages that are not primarily functional, such as Java and, to some extent, Python.

I believe that the single practice that has had the largest impact on making my code contain less errors is just that -- the use of functional principles and ideas. I am not sure exactly which of these principles are most important, but I believe they include:

- The use of very regular data structures, such as lists, maps, and sets
- No special cases in data structures, e.g. using an empty list instead of a special value to signal "no value"
- The use of `map`, `filter`, `reduce`, `zip` and similar to operate on the data structures, rather than traditional, imperative looping constructs
- Immutable data structures

To me, there are two things in particular that stand out in making Clojure very interesting -- the fact that it is a Lisp language, and that it runs on the JVM. I have never been particularly fond of Java as a programming language, but the JVM is a very interesting deployment platform.

Also, it seems the Clojure community hosts a number of very thoughtful individuals, among them Rich Hickey, the inventor of Clojure. If you have not already seen them, here is a list of some very good presentations by Rich:

- [Are We There Yet?](http://www.infoq.com/presentations/Are-We-There-Yet-Rich-Hickey)
- [Simple Made Easy](http://www.infoq.com/presentations/Simple-Made-Easy)
- [Hammock-Driven Development](http://blip.tv/clojure/hammock-driven-development-4475586)

This post has been mostly about my own history in Lisp and functional programming. In later post I will report on my progress in learning Clojure, as well as how I use functional ideas in my everyday programming.