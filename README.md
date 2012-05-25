Nil theme
========================================================================

![Nil theme](https://github.com/nilium/st2-nil-theme/raw/master/screenshot.png)
_Nil UI theme for Sublime Text 2_

This theme is based on [Raik Ilves's Pseudo OSX
theme](https://github.com/raik/st2-pseudo-osx-theme), which is in turn
based on [Ian Hill's Soda theme](https://github.com/buymeasoda/soda-
theme).  Additionally, this theme was inspired by [Liam Cain's Refresh
theme](https://github.com/BoundInCode/st2-refresh-theme), which is also
a variant of Pseudo OSX. So, it's worth noting that Raik's made a pretty
handy base for new themes. I recommend checking out both of them if this
doesn't do it for you (and it's rough around the edges, so it may not).

_A couple of Raik's notes follow because they're pertinent_

Scrollbars are from the default theme.

So I mainly didn't do anything. (N: Same. Just created images and
colors.)


Installation
------------------------------------------------------------------------

You can download or clone the repository into your Sublime Text 2
`Packages` directory. To do this, simply navigate to
`~/Library/Application Support/Sublime Text 2/Packages` (or wherever it
is on your particular operating system) and run the following command:

	git clone git://github.com/nilium/st2-nil-theme.git 'Theme - Nil'

It's **very important** you clone the repository into the `Theme - Nil`
directory otherwise the theme won't locate its assets and will take on
an eldritch appearance. You don't want [Shub-Niggurath][shubby] crawling
out of your screen, so remember, put it in the right directory.


Manually Downloading
------------------------------------------------------------------------

Rename the folder to `Theme - Nil` and put it in your `Packages`
directory.  That's it.


Activating
------------------------------------------------------------------------

In your `Settings - User` file (hit ⌘, on Mac OS to open it), set the
`theme` key to `"Nil.sublime-theme"`, like so:

    {
        "theme": "Nil.sublime-theme"
    }

Assuming you have then installed it correctly, it should show the theme.
Due to what I assume is settings from previous themes surviving, you may
wish to restart Sublime Text 2 as well, but otherwise you should be good
to go.



[shubby]: http://en.wikipedia.org/wiki/Shub-Niggurath