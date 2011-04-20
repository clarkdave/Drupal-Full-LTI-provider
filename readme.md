# Drupal Full LTI provider

This module is an example Full LTI provider using the [LTILib](https://github.com/clarkdave/LTILib) library.

## Features

 * Register multiple consumers
 * Create pages on-demand for incoming lti\_menu\_view\_request calls
 * Create users on-demand using the username from the consumer
 * Understands consumer privilege levels, so consumer administrators will be Drupal administators too

## Usage

A VLE implementing the Full LTI specification (or a subset thereof) can register the Drupal tool can register the tool using the url *http://<url-to-drupal-install>/?lti\_deploy*. This will register the VLE consumer in the Drupal database and allow further request from the consumer to be authenticated.

## Requirements

 * Drupal 7
 * [LTILib](https://github.com/clarkdave/LTILib)
 * A VLE which has an implementation of the Full LTI spec
 ** e.g. The [eile](http://code.google.com/p/eile/) project for Moodle
 
## License 

(The MIT License)

Copyright (c) 2010-2011 Dave Clark (me@clarkdave.net)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.