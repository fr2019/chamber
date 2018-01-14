# Chamber
[![Gem Version](https://img.shields.io/gem/v/chamber.svg)](https://rubygems.org/gems/chamber) ![Rubygems Rank Overall](https://img.shields.io/gem/rt/chamber.svg) ![Rubygems Rank Daily](https://img.shields.io/gem/rd/chamber.svg) ![Rubygems Downloads](https://img.shields.io/gem/dv/chamber/stable.svg) [![Build Status](https://img.shields.io/travis/thekompanee/chamber/master.svg)](http://travis-ci.org/thekompanee/chamber) [![Code Climate](https://codeclimate.com/github/thekompanee/chamber.svg)](https://codeclimate.com/github/thekompanee/chamber) [![Code Climate](https://codeclimate.com/github/thekompanee/chamber/coverage.svg)](https://codeclimate.com/github/thekompanee/chamber)

Chamber is the auto-encrypting, extremely organizable, Heroku-loving,
CLI-having, non-extra-repo-needing, non-Rails-specific-ing, CI-serving
configuration management library.

We [looked at all of the options out there][comparison] and thought something
was still missing, so we wrote Chamber.  We made it with lots of ❤ and we hope
you like it as much as we do.

## Our Ten Commandments of Configuration Management

<img src="https://kompanee-public-assets.s3.amazonaws.com/readmes/chamber-ten-commandments.png" align="right" />

1. Thou shalt be configurable, but use conventions so that configuration isn't
   necessary
1. Thou shalt seamlessly work [with Heroku][heroku] or other deployment
   platforms, where custom settings may be stored in
   [environment variables][env-vars]
1. Thou shalt seamlessly work with [Travis CI][travis] and other cloud CI
   platforms
1. Thou shalt not force users to use arcane
   [long_variables_to_keep_their_settings_organized][accessing]
1. Thou shalt not require users keep a separate repo or cloud share sync just to
   [keep their secure settings updated][encryption]
1. Thou shalt not be bound to a single framework like Rails (it should be usable
   in other frameworks as well as [in plain Ruby projects][plain-ruby])
1. Thou shalt have an [easy-to-use CLI][cli] for scripting
1. Thou shalt allow certain settings to be
   [encrypted separately][namespace-keys] to allow levels of access.
1. Thou shalt be [well][inch] [documented][wiki] with full test coverage
1. Thou shalt not have to worry about [accidentally committing][commit-hook]
   secure settings

## Basic Usage

You can view our Basic Usage Guide [here][basic-usage].  Otherwise, for the full
Chamber guide, visit the [wiki][wiki].

## Credits

Chamber was written by [Jeff Felchner][jeff-profile] and
[Mark McEahern][mark-profile]

![The Kompanee][kompanee-logo]

Chamber is maintained and funded by [The Kompanee, Ltd.][kompanee-site]

The names and logos for The Kompanee are trademarks of The Kompanee, Ltd.

## License

Chamber is Copyright © 2014-2018 Jeff Felchner and Mark McEahern. It is free
software, and may be redistributed under the terms specified in the
[LICENSE][license] file.

[accessing]:      https://github.com/thekompanee/chamber/wiki/Accessing-Settings
[basic-usage]:    https://github.com/thekompanee/chamber/wiki/Basic-Usage
[cli]:            https://github.com/thekompanee/chamber/wiki/CLI-Overview
[commit-hook]:    https://github.com/thekompanee/chamber/wiki/Git-Commit-Hooks
[comparison]:     https://github.com/thekompanee/chamber/wiki/Gem-Comparison
[encryption]:     https://github.com/thekompanee/chamber/wiki/Encryption-Basics
[env-vars]:       https://github.com/thekompanee/chamber/wiki/Environment-Variables
[heroku]:         https://github.com/thekompanee/chamber/wiki/Heroku
[inch]:           https://inch-ci.org/github/thekompanee/chamber
[jeff-profile]:   https://github.com/jfelchner
[kompanee-logo]:  https://kompanee-public-assets.s3.amazonaws.com/readmes/kompanee-horizontal-black.png
[kompanee-site]:  http://www.thekompanee.com
[license]:        https://github.com/thekompanee/chamber/blob/master/LICENSE.txt
[mark-profile]:   https://github.com/m5rk
[namespace-keys]: https://github.com/thekompanee/chamber/wiki/Namespaced-Key-Pairs
[plain-ruby]:     https://github.com/thekompanee/chamber/wiki/Installation#in-a-ruby-project-or-ruby-gem
[travis]:         https://github.com/thekompanee/chamber/wiki/TravisCI
[wiki]:           https://github.com/thekompanee/chamber/wiki
