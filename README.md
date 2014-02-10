Sublime-Logos
=============

Logos syntax highlighter for Sublime Text.

Stick the .tmLanguage file in `~/Library/Application Support/Sublime Text 2/Packages/User` and reload Sublime (close and reopen). You should now have syntax highlighting for logos.

<del>It could be better, a lot better. I do not know regexes enough to fix it, but if anyone feels like contributing, it would be appreciated.</del>

### Notes
**tl;dr;** It's far nicer than what's offered, but may still break! :D

I added Objective-C's tmLanguage from the Sublime app directly to this so customization would be easier (still don't fully understand Sublime's includes and such for syntax definitions), so this may break in the future.

%init and %hook make much more sense now when picked up, and don't break Sublime Text's Objective-C syntax definitions. Cleaned up some other variable recognition as well as property invocations (obj.doThis.doThat, etc.).

Haven't tried it on Sublime Text 2, since I've fully switched to 3.
