# TeXtheWorld Safari Extension

## Abstract
This is an extension for Safari to support embedded [LaTeX](http://www.latex-project.org) on Reddit. This was originally done because installing Ninjakit (a GreaseMonkey clone for Safari) fell off the radar and it seemed simpler to just make an extension for personal use.

## Get the Extension
A prebuilt extension that has been briefly tested with Safari 10.1.1 and Safari 10.2 (Technology Preview) is available [here](https://github.com/anavaino/TeXtheWorld/raw/master/TeXtheWorld.safariextz). It will require you to trust it since it's not a published extension. *Caveat emptor*. If you have issues with it, report them [here](https://github.com/anavaino/TeXtheWorld/issues) or send a message to [/u/Anavaino](https://www.reddit.com/message/compose/?to=Anavaino) on Reddit.

## Is It Working?
You can see if it's working for you by going to [/r/math](https://www.reddit.com/r/math) and scrolling down to the **Using LaTeX** section on the sidebar. Depending on how you installed it and answered dialogs, it may be installed but not enabled. In Safari, press ⌘-, (command-comma) or select Safari->Preferences... from the menu bar, then click Extensions at the top and check the box next to *TeXtheWorld* to enable it.

## Detail
This is an extremely simple Safari extension that runs TeXtheWorld Javascript in Safari on Reddit. It was written in roughly
10 minutes in order to see the embedded LaTeX used on Reddit's [/r/math](https://www.reddit.com/r/math). Writing this README and creating the repository took far longer. The Javascript came
directly from [a link](http://thewe.net/tex/textheworld7.user.js) in /r/math's sidebar. The suggestion to Open Source it came from Reddit user
[/u/sheyneanderson](https://www.reddit.com/user/sheyneanderson) since the author (me - your brother) was too stupid to think of it himself.

It's configured to run on all of Reddit, but nowhere else. You can easily modify this using Safari's built-in
Extension Builder. Apple's documentation for it is [here](https://developer.apple.com/library/content/documentation/Tools/Conceptual/SafariExtensionGuide/Introduction/Introduction.html).

## References & License
The bulk of the work comes from [thewe.net](http://thewe.net) via their currently (25 May 2017)
[unmaintained](http://thewe.net/tex/) Javascript.

The permissive [MIT License](https://en.wikipedia.org/wiki/MIT_License) has been applied to this; however, it does not
apply to the TeXtheWorld Javascript since it *seems* to come unlicensed. The intent is not to restrict this but rather to
protect it from being taken over by someone intending to commercialize it with no recourse. A recent
[Bourbaki](https://en.wikipedia.org/wiki/Nicolas_Bourbaki) study ranked TeX extensions as one of the most commericially
profitable browser extensions in the history of the World Wide Web[\*](https://en.wikipedia.org/wiki/Poe's_law). One can never be to cautious.
