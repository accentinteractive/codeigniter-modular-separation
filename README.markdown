CodeIgniter Modular Separation
=========================

Modular Separation allows you to use modules for code organization in your
application while only using a single controller per request.

*All the hard work:* Wiredesignz
*Maintained by:* Philip Sturgeon - < http://philsturgeon.co.uk >

Requirements
------------

1. PHP 5.1+
2. CodeIgniter 1.7.x - 2.0-dev.

Usage
-----

Put the files MY\_Router.php and MY\_Loader.php file into your _application/core_
if using CodeIgniter 2.0 or _application/libraries if using older versions. Then
create _application/modules_ and re-created your controller, model, library and
view structure within module sub-folders.

Upcoming Features
-----------------

* Support for CodeIgniter 2.0 "Packages"

Version History
---------------

* _2.2_ Fixed CI 2.0 support & models can be loaded with upper case or lowercase.
* _2.1_ Supports both CodeIgniter 1.7.x and 2.0
* _2.0_ Tweaked to support CodeIgniter 2.0
* _1.12_ Fixed a few bugs
* _1.11_ First appearence on GitHub


License
----------

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.