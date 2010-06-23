nanoc+Compass bootstrap project
===============================

This directory contains a small nanoc project that uses Compass. It is based on a brand new nanoc site generated using `nanoc3 create_site`.

Places of interest:

* `config.rb` which contains the Compass configuration
* `content/style` which contains the Sass stylesheets (and a partial)
* `Rules` which contains the rules for processing the Sass stylesheets

How To Use
----------

Before you do anything, make sure that you have Compass installed. Issue `gem install compass` if you haven't already or if you're unsure.

To compile the site, simply use `nanoc3 co`.

You may want to edit the Compass configuration (`config.rb`) to suit your needs.


Including Susy
--------------

This variation of ddfreyne's bootstrap project includes [Susy](http://susy.oddbird.net/) 0.7.0, which is a fluid layout template system. Ensure that you have run "gem install compass-susy-plugin" before you try to use this.

I've also converted the Susy stylesheets from .scss to .sass, and all .html to .haml, to accommodate my personal preferences.