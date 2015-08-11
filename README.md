meadowlark
==========

The custom theme for my [Pelican]-based blog.

Installation
------------

This theme requires [Less CSS][less] (`npm install -g less`) and [webassets]
(`pip install webassets`). You will also need the `assets` plugin for Pelican,
which you can get from the [`pelican-plugins` repository][plugins].

If you want to use Disqus, note that you should set up the full Comment Count
Link, as no additional text is applied. For example, mine are:

 - "There are no comments"
 - "There is one comment"
 - "There are {num} comments"

About
-----

The theme is a custom job, but it draws heavily from Pelican's base `notmyidea`
theme by [Smashing Magazine][sm]. Another inspiration was [Campo Santo][cs],
whose website I borrowed extensively from (the name is a reference to their
forthcoming game [Firewatch]; it's the state bird of Wyoming, where the game
is set).

The icons in the right-hand link bar are from [Font Awesome][fa] by Dave Gandy.
The pure HTML/CSS "Fork me on GitHub" ribbon is based on
[`github-fork-ribbon-css`][ghfr] by Simon Whitaker; I modified it to be flatter
and use Keith Bates' [Collegiate] font.

  [collegiate]: http://www.fontriver.com/font/collegiate/
  [cs]: http://www.camposanto.com/
  [fa]: http://fontawesome.io/
  [firewatch]: http://www.firewatchgame.com/
  [ghfr]: https://github.com/simonwhitaker/github-fork-ribbon-css
  [less]: http://lesscss.org/
  [pelican]: http://getpelican.com/
  [plugins]: https://github.com/getpelican/pelican-plugins.git
  [sm]: http://www.smashingmagazine.com/2009/08/04/designing-a-html-5-layout-from-scratch/
  [webassets]: https://webassets.readthedocs.org/en/latest/
