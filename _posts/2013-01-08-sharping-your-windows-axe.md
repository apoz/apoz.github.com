---
layout: post
category : general
tags : [ windows, development ]
---
{% include JB/setup %}


> If I had eight hours to chop down a tree, I would spend six hours sharpening my axe.
> Abraham Lincoln

We've all been there: you want to do some development or test something new with your beloved Windows machine and at the end you spend more time dealing with dependencies that doing what you actually wanted to do.
Most of the times this happens because our Windows is not 'properly sharpened' for these kind of tasks.
This post just wants to gather some links about what SHOULD be done in a Windows machine for preparing it for these tasks and spend more time hacking than preparing Windows for your hacks ;)

The beginning...
-------------------
[This article](http://windowssecrets.com/top-story/seven-simple-steps-for-setting-up-windows-7/) shows some stuff that you have to do in the beginning: create common users, make your backups run, get rid of crap PC vendors install with [Decrapifier](http://www.pcdecrapifier.com) and so on. Worth a look to the article.
For the initial software installation _or after a hard disk format_ I strongly recommend using [Ninite](http://ninite.com/), a great website that creates a custom installer for most of the pieces of software you probably are going to install.

If you want to code...
----------------------
The short list of things that will help you if you want to code:

*   _Choose a good editor and_ __MASTER__ _it_: [Notepad++](http://notepad-plus-plus.org/) is not a bad choice but you HAVE to know (at least the basics) of the classics [Vim](http://vim.org) or [Emacs](http://www.gnu.org/s/emacs/). If you want to be as cool a as Mac user, you can choose _and pay_ [Sublime](http://www.sublimetext.com/) too :P
*   _Know how to handle environment variables_: Pretty basic but you will have to [modify some variables](http://www.itechtalk.com/thread3595.html) like PATH, CLASSPATH, etc...
*   _Change the damn windows command line (CMD)_: Seriously they had no time to improve it since Windows95???  Get a decent command line ASAP: [PowerCMD](http://www.powercmd.com/) is pretty good!
*   _Get a C/C++ compiler in your PATH_: Handling dependencies is always a pain. Sometime in your life you are going to need to compile something, for an installation with Make or for some module, so go get [minGW](http://minGW.org), install it and set it in your PATH variable. It will be useful.

And I think that are the basics. From this point on you just have to install your [favorite CVS](http://git-scm.com/download/) and the [language](http://www.python.org/getit/windows/) you [plan](http://rubyinstaller.org/) to [work](http://www.java.com/es/download/).
Your windows axe should be sharp enough for you not to have a lot of problems.

 Happy windows hacking!
