CUSS - Constantly Updating Style Sheets
=======================================

Overview
--------

Cuss is a utility for watching a folder for file changes to various css
precompilers and automatically recompiling the templates when they are saved.

Support
-------
Cuss will support [SASS].

Future iterations will add support for:

* [SCSS]
* [LESS]
* [Stylus]

Not CSS
-------

Some consideration has been given to adding support for JavaScript and HTML
preprocessors. One problem I forsee is that these preprocessors tend to allow
for interpolation of variables which have to come from... somewhere. And I don't
want to provide them.

Nevertheless, support could be accomplished provided fairly simply provided you
promise not to assume that cuss will give you any variables outside of what you
declare in your file.

### HTML

* [HAML]
* [ERB]
* [Mustache]
* [Markdown]
* [Textile]
* [RDoc]
* [Mediawiki]
* ...

### Javascript

* [Coffee]
* [IcedCoffee]

Dependencies
------------

[FSSM] &ndash; Used for monitoring folders for file changes.

Gems to support each preprocessor.

[scss]: sass-lang.com
[sass]: sass-lang.com
[less]: lesscss.org
[haml]: haml-lang.com
[stylus]: http://learnboost.github.com/stylus/
[erb]: http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html
[markdown]: daringfireball.net/projects/markdown
[mustache]: https://github.com/defunkt/mustache
[textile]: http://redcloth.org/textile
[rdoc]: https://github.com/rdoc/rdoc
[mediawiki]: http://www.mediawiki.org/wiki/Help:Formatting
[coffee]: coffeescript.org
[icedcoffee]: http://maxtaco.github.com/coffee-script/
[fssm]: https://github.com/ttilley/fssm