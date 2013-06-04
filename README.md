Nil Theme
------------------------------------------------------------------------

![Nil theme](https://github.com/nilium/st2-nil-theme/raw/master/dark.png)  
_Nil UI theme for Sublime Text 2_

Nil is the dark theme for the overall Nil theme package.  Yes, there's
a light theme -- scroll down if that's what you want.  They're both in
the same repository, though they have different names just to be fancy.
The color scheme pictured above is Big Duo.

This theme is based on [Raik Ilves's Pseudo OSX
theme](https://github.com/raik/st2-pseudo-osx-theme), which is in turn
based on [Ian Hill's Soda theme](https://github.com/buymeasoda/soda-
theme).  Additionally, this theme was inspired by [Liam Cain's Refresh
theme](https://github.com/BoundInCode/st2-refresh-theme), which is also
a variant of Pseudo OSX. So, it's worth noting that Raik's made a pretty
handy base for new themes.I recommend checking out both of them if this
doesn't do it for you (and it's rough around the edges, so it may not).

Overlay scrollbars are kindly borrowed from the default theme.


Ayin Theme
------------------------------------------------------------------------

![Ayin theme](https://github.com/nilium/st2-nil-theme/raw/master/light.png)  
_Ayin UI theme for Sublime Text 2_

Ayin is the light theme of the Nil theme package.  It features a lot of
grey and arguably softer colors, though should still remain as pseudo-
functional as its dark counterpart. The color scheme pictured above is
Tubnil Bright.


Color Schemes
------------------------------------------------------------------------

The Nil theme package comes with the two color schemes seen in the both
the light and dark screenshots respectively:

* `Tubnil.tmTheme` → My personal variation of the Tubster theme for
  TextMate.  This is the original dark color scheme.

* `Tubnil Bright.tmTheme` → A variation on the above Tubnil theme for
  folks who like bright color schemes.

* `Big Duo.tmTheme` → Another variation on Tubnil, this time with
  a slightly lighter background color, arguably less intense colors,
  and so on. Cast in the name of god and all that.

Both can be found in the root directory of the package, so to use it
either, simply point your `color_scheme` preference to
`Theme - Nil/Tubnil.tmTheme` or one of the other color schemes.


Options
------------------------------------------------------------------------

There are a handful of options you can use to customize the appearance
of both the Nil and Ayin themes. All options are boolean values and
disabled by default. Their keys and descriptions follow:

* `highlight_modified_tabs` — If true, will display an orange bar under
  tabs with modified buffers.
* `sidebar_folders` — If true, will display a folder icon beside folders
  in the sidebar instead of a disclosure triangle. Sidebar folders are
  off by default.
* `colored_folder_glyphs` — If true, will tint either folder icons or
  disclosure triangles in the sidebar (only the sidebar) purple.
* `disable_colored_group_labels` — If true, will disable the colored
  group labels. Group labels are the things that say "Group 1" and 2 and
  so on in the sidebar. They're only visible if you have open files
  shown. Colored group labels are enabled by default.
* `disable_colored_folder_labels` — If true, will disable the colored
  folder labels in the sidebar. This is independent of group label
  coloring. Colored folder labels are enabled by default.

To set any of these properties, place them and their values in your user
preferences file.


HDPI Displays
------------------------------------------------------------------------

This theme includes HDPI images for displays that support HDPI on Mac
OS X, such as the recent (as of this writing) MacBook Pro with the
retina display.  Both screenshots above are in HDPI.


Fonts
------------------------------------------------------------------------

In the above screenshots, the font in use is [PragmataPro], designed by
Fabrizio Schiavi. In previous screenshots, the font in use was [Envy Code R],
by Damien Guard. The former is an excellent font, but is not free. The
latter is also an excellent font and free. Neither font ships with this
theme package. My personal preference these days is PragmataPro, but I
had no particular font choice in mind for the theme and the important
thing is that you use what you like.

[PragmataPro]: http://www.fsd.it/fonts/pragmatapro.htm
[Envy Code R]: http://damieng.com/blog/2008/05/26/envy-code-r-preview-7-coding-font-released


Installation
------------------------------------------------------------------------

#### Package Control

If you have Package Control installed, you simply need to open the
Package Install window and select "Theme - Nil". After that, skip ahead
to the "Activating" section of this README.


#### Installation via Git

You can download or clone the repository into your Sublime Text 2
`Packages` directory. To do this, simply navigate to
`~/Library/Application Support/Sublime Text 2/Packages` (or wherever it
is on your particular operating system) and run the following command:

	git clone git://github.com/nilium/st2-nil-theme.git 'Theme - Nil'

It's **very important** you clone the repository into the `Theme - Nil`
directory otherwise the theme won't locate its assets and will take on
an eldritch appearance. You don't want [Shub-Niggurath][shubby] crawling
out of your screen, so remember, put it in the right directory.

[shubby]: http://en.wikipedia.org/wiki/Shub-Niggurath


#### Manually Downloading

If you choose to download an archive of this repo from GitHub, you must
rename the extracted folder to `Theme - Nil` and put it in your
`Packages` directory.  That's it -- simple.


Activating
------------------------------------------------------------------------

In your `Settings - User` file (hit ⌘, on Mac OS to open it), set the
`"theme"` key to `"Nil.sublime-theme"` or `"Ayin.sublime-theme"`, like
so:

    {
        "theme": "Nil.sublime-theme"
    }

**or**

    {
        "theme": "Ayin.sublime-theme"
    }

Assuming you have then installed it correctly, it should show the theme.
Due to what I assume is settings from previous themes surviving, you may
wish to restart Sublime Text 2 as well, but otherwise you should be good
to go.
