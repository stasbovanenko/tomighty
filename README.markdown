Tomighty is...
==============

A desktop timer app that helps you apply the Pomodoro Technique.
It's written in Java and designed to be simple, easy to use and unintrusive.

Know more about it at [www.tomighty.org](http://www.tomighty.org)

Building
--------

Regardless of your operating system, you must have the following things installed on it and included in your path:

  * JRE 1.5 or greater
  * Maven 2.x or greater
  * Git

Under Windows platform you also must have:

  * NSIS 2.x or greater

Open a system shell and check out the sources into some directory. Then `cd` into that directory and type:

  `mvn clean package`

The resulting built artifacts will be located under the `target` directory. That's it.

