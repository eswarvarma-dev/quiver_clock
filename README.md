Quiver Clock
======

Move around in time and make your programs testable by abstracting from system
clock.

[![Build Status](https://travis-ci.org/QuiverDart/quiver_clock.svg?branch=master)](https://travis-ci.org/QuiverDart/quiver_clock)
[![Coverage Status](https://img.shields.io/coveralls/QuiverDart/quiver_clock.svg)](https://coveralls.io/r/QuiverDart/quiver_clock)

[API Docs](http://www.dartdocs.org/documentation/quiver_clock/latest) are available.

`Clock` provides points in time relative to the current point in time, for
example: now, 2 days ago, 4 weeks from now, etc. For tesability, use Clock
rather than other ways of accessing time, like `new DateTime()`, so that you
can use a fake time function in your tests to control time.
