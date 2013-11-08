# Ember States [![Build Status](https://travis-ci.org/emberjs/ember-states.png)](https://travis-ci.org/emberjs/ember-states)

The Ember States API: state machine built for Ember.

## Up and running in less than a minute

1. Download the [latest build](http://builds.emberjs.com/ember-states/latest/ember-states.js).
2. In your application, include ember-states.js immediately after Ember.
3. Enjoy!

## Building

1. Run `bundle install` to fetch the necessary ruby gems.
2. Run `rake dist` to build Ember.js. Two builds will be placed in the `dist/` directory.
  * `ember-states.js` and `ember-states.min.js`

If you are building under Linux, you will need a JavaScript runtime for
minification, for which we recommend installing nodejs.  Alternatively
you may have luck with another of the runtimes supported by
[execjs](https://github.com/sstephenson/execjs).

## How to Run Unit Tests

### Setup

1. Install Ruby 1.9.3+. There are many resources on the web can help;
one of the best is [rvm](https://rvm.io/).

2. Install Bundler: `gem install bundler`

3. Run `bundle` inside the project root to install the gem dependencies.

### In Your Browser

1. To start the development server, run `rackup`.

2. Then visit: `http://localhost:9292/`

### From the CLI

1. Install phantomjs from http://phantomjs.org

2. Run `rake test` to run a basic test suite or run `rake test[all]` to
   run a more comprehensive suite.

3. (Mac OS X Only) Run `rake autotest` to automatically re-run tests
   when any files are changed.
