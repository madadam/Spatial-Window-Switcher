Spatial Window Switcher
=======================

Description
-----------

Spatial Window Switcher (sws) is a simple tool to switch between open windows
according their spatial placement. It allows you to switch to window to the
left, right, above or below the active window. It works across multiple monitors
and multiple desktops.

Usage
-----

The best way to use this tool is to map it to global keyboard shortcuts of your
desktop environment:

| Action                            | Command     |
|-----------------------------------|-------------|
| Switch to the window to the right | `sws right` |
| Switch to the window to the left  | `sws left`  |
| Switch to the window above        | `sws above` |
| Switch to the window below        | `sws below` |

For example, in Ubuntu, open up the Keyboard settings, switch to the Shortcuts
tab, go to Custom Shortcuts. Then Click the `+` button on the bottom and add
each one of the the above actions. Then assign then shortcuts according to your
preference.

Requirements
------------

This tool is written for linux. It depends on [wmctrl](http://tomas.styblo.name/wmctrl/),
xprop (part of X Window system) and [ruby](https://www.ruby-lang.org/en/).

Limitations
-----------

The spatial searching algorithm is currently very simplictic and in might not
switch to the expected window. This will improve in the future.

Licence
-------

The MIT License (MIT)

Copyright (c) 2014 Adam Cigánek <adam.ciganek@gmail.com>

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