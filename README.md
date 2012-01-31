# ninjafly.el

## What is it?

A fork of Google's awesome Ninja build integration for [flymake][1].

## Why the fork?

My version adds one feature: the ability to specify a list of files to consider as candidates for a project's build file instead of being locked into using a single file.  This makes it easier to set up Ninja and Flymake and have them work together over a bunch of different projects.

Also, I liked the name :p

## Credits

This wonderful code was almost fully written by the good folks over at Google for the [Chromium project][2]

[1]: http://www.emacswiki.org/emacs/FlyMake
[2]: http://src.chromium.org/svn/trunk/src/tools/emacs/flymake-chromium.el
