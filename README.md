# That's Mood v.8
Version 8 of the site thatsmood.com

October 2019

## About
Finally making the transition from a Wordpress site to a static generated one.
The site will use Jekyll as the generator and Disqus to handle comments to posts.
All content from the old site will be transferred.


## Requirements
* [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.2.5 or above, including all development headers
* [RubyGems](https://rubygems.org/pages/download)
* [GCC](https://gcc.gnu.org/install/) and [Make](https://www.gnu.org/software/make/)
* [Bundler](https://bundler.io/)
* [Jekyll](https://jekyllrb.com/)

## Set up the local environment
**Note:** _Make sure your system satisfies the requirements above_

* Run in the terminal `gem install bundler jekyll`
* Clone the repository `git clone git@github.com:ginestra/thatsmood-v8.git`
* `cd` into the repository
* Install everything you need in your project folder (rather than at system level): `bundle install --path bundle && bundle install`

## Run locally

* Run in the terminal `bundle exec jekyll serve --watch --incremental` (the flags `--watch` and `--incremental` are optional, they are useful if editing the project)
* The site is now locally accessible at `http://localhost:4000/`