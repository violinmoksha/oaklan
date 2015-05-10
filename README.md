oaklan
======

"oaklan" custom wordpress theme is based on _strap (https://github.com/ptbello/_strap). _strap (per their readme.md) "is a WordPress theme with the goal of integrating Twitter's bootstrap into Automattic's _s with the smallest possible changeset." _s, pronounced "underscores" (https://github.com/Automattic/_s) is a starter skeleton theme for WordPress which was not Bootstrap-equipped, thus oaklan is based on _strap, a skeleton theme based on _s, but having Bootstrap.

Thus the technical rationale for creating "oaklan", based off of _strap Bootstrap-ready skeleton code. The design rationale for "oaklan" derives from zenverse's free web design/development portfolio theme "blacktribe," but when I wanted to update my web portfolio site's hacked blacktribe theme code to be mobile-friendly in the wake of Google's 2015 "mobilegeddon" update, I realised blacktribe was not RWD/responsive, and talked to the WordPress API in many outdated sorts of ways, thus I created "oaklan"...

So, anyone looking for a free theme like blacktribe, but which is html5 semantic, responsive, etc., and which they want to house their professional-looking web portfolio in, can possibly find what they're looking for in oaklan.

Installation
------------
1. Download the .zip
2. Unpack it to your /wp-content/themes directory.
3. Log in to your WordPress backend and activate it

Configuration (this is v0.1, more wordpress admin config hooks integration coming in a new version soon)...
------------
Have each Post you want appearing in the Bootstrap carousel-powered animated slider on the front page of your site (like the one you see on http://oaklandesigns.com) containing a reference to a website you had some major notable contributions to. If you want the Post to appear in your front page slider, simply use oaklan's custom-provided form entries injected into the bottom of the "Edit Post" admin area of your wordpress, to provide a thumbnail image (to be rendered in that portfolio Post), and a larger slider image for the mention of the portfolio item in the front-page slider. That's it!

More configuration options akin to the original blacktribe theme coming soon in v0.2 etc.

What you get/What you put
------------
Since _strap was LESS-based for its .css, I've added a small, portable package.json for a nodejs gulp-based LESS auto-save transpiler. Thus, if you decide you want to custom edit oaklan and turn it into something else, you'll need to edit or add to the included .less files, change the paths around, and auto-transpile your LESS into uglified/minified and gzip'd .css by running gulp in the background. Anyone who knows node, npm, and gulp (or grunt) should be able to figure out what to do with this package.json ... (I've also left the gulpfile.js around for you to hack around with to your heart's content) ;-)

Example
------------
If you install and configure as above, you should get something that looks like this (and is fully response to mobile/tablet/desktop):

<a href="http://oaklandesigns.com"><img src="https://github.com/violinmoksha/oaklan/raw/master/screenshot.png" alt="a screenshot of oaklandesigns.com"></a>
