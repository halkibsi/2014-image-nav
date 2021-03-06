# Twenty Fourteen Enhanced Image Navigation

Image navigation enhancements for the [Twenty Fourteen](http://twentyfourteendemo.wordpress.com/) default WordPress theme. Initially created as a demo for a [WP Sessions](http://wpsessions.com) presentation on JavaScript Unit Testing.

* Author: K.Adam White
* Version: 0.1
* Author URI: http://www.kadamwhite.com/
* License: GPLv3 or later
* License URI: http://www.gnu.org/licenses/gpl-3.0.html

## Running the tests

The tests for this library are written in [QUnit](http://qunitjs.com), which we install using [Bower](http://bower.io/). From the root of the repository in a terminal window, run `bower install` to download and install jQuery and QUnit. Then open [tests/qunit-tests.html](tests/qunit-tests.html) to run the tests.

**Running tests from the command line with Grunt**

It is possible to run the tests automatically from the command line using the [Grunt](http://gruntjs.com) JavaScript task runner. To use Grunt,

1. Install the Grunt <acronym title="Command Line Interface">CLI</acronym> by running `npm install -g grunt-cli`.
2. Install the packages needed by this repository by running `npm install` from the root of the repository.
3. Run `grunt` to run the unit tests & check your code for syntax errors.
