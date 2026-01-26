+++
date = '2025-11-23T13:16:45+13:00'
draft = false 
title = 'Down the (fire)foxhole'
+++
This weekend I decided to add Mozilla Firefox support for my [IPONZ Linker Chrome extension](https://chromewebstore.google.com/detail/iponz-linker/ekoaiaoikoakfaddefogbojeokkehngk), mainly because Firefox supports extensions on mobile.

Since I use Chrome APIs like [chrome.storage](https://developer.chrome.com/docs/extensions/reference/api/storage), I was checking whether I needed to swap when I came across a comment that mentioned "chrome" is UI jargon that might have been originally coined by Mozilla.

Curiosity led me down a rabbit hole of deep browser lore.

In 1997 while working at Netscape, engineer Dave Hyatt wrote the first specification of XUL (pronounced /zool/ as a Ghostbusters reference), standing for XML-based User Interface Language. In the context of XUL, "chrome" referred to the top level window containing groups of UI elements, so anything making up the UI of the application (as opposed to content) was considered "chrome". XUL was used to help rewrite the UI of the Netscape browser, which was open-sourced in 1998 and became the Mozilla project. A search for "chrome" in an [archive of the 1998 codebase](https://github.com/zii/netscape) shows many instances throughout.

At this point [Ben Goodger](https://www.linkedin.com/in/bengoodger/) began contributing to the Mozilla project while studying engineering at the University of Auckland (where all the coolest people go), and was hired at Netscape where he collaborated with Dave Hyatt and others on XUL and the Mozilla suite.

In early 2002 Dave Hyatt and colleagues started development of a new standalone browser unburdened by the bloat of the Mozilla suite - which eventually became Mozilla Firefox. Around the same time Dave also built the Camino browser for Mac OS. Perhaps this drew Apple's attention because in July 2002 they recruited him to work on Safari, which released in January 2003.

Meanwhile, Ben Goodger took up work on Firefox in the leadup to its 1.0 release in 2004, and became its lead developer. In January 2005 he was [recruited by Google](https://arstechnica.com/uncategorized/2005/01/4549-2/), but they kept him working on Firefox - presumably to drive web adoption and attract further talent. 

Ben soon referred a few Apple engineers on the Safari team to Google including Dave Hyatt. However, Steve Jobs was outraged and made numerous angry phone calls to Google founders Larry Page and Sergey Brin in February 2005, as well as their mutual mentor Bill Campbell (CEO of Intuit), saying it was war if they stole his browser guy. 

We know this because Steve's tactics led to a [significant antitrust lawsuit](https://en.wikipedia.org/wiki/High-Tech_Employee_Antitrust_Litigation) years later implicating Google, Apple, and Intuit, with numerous internal emails made public. 

Although Google failed to recruit the legendary browser guy, Dave announced on his blog in June 2025 that Apple was open-sourcing Safari's WebKit engine. Ben and another former Netscaper Darin Fisher then began building a browser for Google in 2006 using WebKit, with the motto "content not chrome" expressing their aim of minimalism in the UI. 

The name Chrome stuck, likely tracing its origins back to the development of XUL at Netscape, and Ben fought to make Chromium an open source project - fitting given the role open source played in his journey and the web's!
