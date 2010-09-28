jquery.pomodoro.js
==================

A pomodoro-style timer for jQuery that is easily pluggable and extensible


Example
-------

Simplest example

    <!DOCTYPE html> 
    <html> 
      <head> 
        <title>Pomodoro Example</title> 
        <script src='http://ajax.googleapis.com/ajax/libs/jquery/1.4.2/jquery.min.js' type='text/javascript'></script>
        <script src='/pomodoro/jquery.pomodoro.js' type='text/javascript'></script> 
        <link href='/pomodoro/pomodoro.css' media='screen' rel='stylesheet' type='text/css'>
      </head> 
      <body> 
        <a href="#" onclick="$.pomodoro(); return false">Start Pomodoro</a>
      </body> 
    </html>


References
----------

I borrowed heavily (both style and code) from Chris Wanstrath's wonderful [Facebox](http://chriswanstrath.com/facebox/)

* [Facebox](http://chriswanstrath.com/facebox/)
* [The Pomodoro Technique](http://www.pomodorotechnique.com/)


Copyright
---------

MIT License

Copyright (c) 2010 Brian Smith <bsmith@swig505.com>

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
