

## Setup

1. Add your site and author details in `_config.yml`.
2. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Edition was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

### Documentation pages

* Add, update or remove a documentation page in the *Documentation* collection.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.

### Navigation

* Change `site.show_full_navigation` to control all or only the current navigation group being open.
