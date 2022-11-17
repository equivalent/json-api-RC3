This is NOT the official JSON-API project, just mirror to it's  RC3 version.

website: http://jsonapi-rc3.herokuapp.com/

> UPDATE 2022-11-17 Heroku will no  longer be free ([source](https://blog.heroku.com/next-chapter))  I'm shutting down the dyno. If anyone wants to host this app / pay for the dyno contact me (contact info [eq8.eu](https://www.eq8.eu/))

Real `>= 1.0` realase is hosted at http://jsonapi.org/ and
https://github.com/json-api/json-api

Original content of RC3 README:

JSON API
========

Documentation for the [application/vnd.api+json media
type](http://www.iana.org/assignments/media-types/application/vnd.api+json),
a standard for APIs that use JSON. This repository is the
source code for [http://jsonapi.org](http://jsonapi.org).


Resources
---------

* IRC channel: #jsonapi on freenode.net
* Twitter: @jsonapi


Status
------

This standard is currently under development. To assist:

1. Get the dependencies:

    `$ bundle`

1. Host the site locally while editing:

    `$ bundle exec rake preview:browser`

1. Edit the Markdown files.
1. Commit your changes.
1. Send a Pull Request when finished.

The website is automatically built by [GitHub Pages](http://pages.github.com)
when changes are pushed to the `gh-pages` branch.
