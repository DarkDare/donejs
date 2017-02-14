@page DoneJS
@hide title
@hide sidebar

![DoneJS logo](https://donejs.com/static/img/donejs-logo-black.svg)

[![npm version](https://badge.fury.io/js/donejs.svg)](https://badge.fury.io/js/donejs)
[![Build Status](https://travis-ci.org/donejs/donejs.svg?branch=master)](https://travis-ci.org/donejs/donejs)
[![Build Status](https://ci.appveyor.com/api/projects/status/github/donejs/donejs?branch=master&svg=true)](https://ci.appveyor.com/project/daffl/donejs)
[![Coverage Status](https://coveralls.io/repos/github/donejs/donejs/badge.svg?branch=master)](https://coveralls.io/github/donejs/donejs?branch=master)

DoneJS is the easiest way to get a high-performance, real-time, web and mobile application
done! The framework provides a nearly comprehensive combination of technologies for
building complex JavaScript applications.

If you are looking for the fastest way to get a fully modern development environment setup
and produce a lightning fast application, you’ve come to the right place.

DoneJS is a combination of the following technologies:

- [StealJS](http://stealjs.com) — ES6, CJS, and AMD module loader and builder
- [CanJS](https://canjs.com) — Custom elements and model-view-viewmodel (MVVM) utilities
- [jQuery](https://jquery.com/) — DOM helpers
- [jQuery++](http://jquerypp.com) — Extended DOM helpers
- [QUnit](https://qunitjs.com/) or [Mocha](https://mochajs.org/) — Assertion library
- [FuncUnit](https://funcunit.com/) — Functional tests
- [Testee](https://github.com/bitovi/testee) or [Karma](https://karma-runner.github.io/) — Test runner
- [DocumentJS](http://documentjs.com) — Documentation
- [can-ssr](https://github.com/canjs/ssr) — Server-side rendering utilities for CanJS

DoneJS is an `npm` package that simply installs all the previous
technologies. Check out [DoneJS.com](https://donejs.com/) for the collective [benefits](https://donejs.com/Features.html) of these technologies
and [guides](https://donejs.com/Guides.html) on how to use them together to build an amazing application.

## Contributing

### Cloning the repository

```
git clone git@github.com:donejs/donejs.git
cd donejs
```

### Installing the dependencies

```
npm install
```

### Running the tests

```
npm test
```

### Building the docs

```
npm run document
```

### Deploying to DoneJS.com

After cloning the repo and installing the dependencies:

```
git clone git@github.com:donejs/donejs.git -b gh-pages site/
```

If you get an error saying `Permission denied (publickey)` then you should follow GitHub’s instructions on
[generating an SSH key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/).

Push a new commit to the `gh-pages` branch with the built docs:

```
npm run document
cd site/
git add --all
git commit -am "Updating site"
git push origin gh-pages
```
