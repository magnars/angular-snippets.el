# angular-snippets.el

Yasnippets for [AngularJS](http://angularjs.org/).

## Installation

I highly recommend installing angular-snippets through elpa.

It's available on [marmalade](http://marmalade-repo.org/) and
[melpa](http://melpa.milkbox.net/):

    M-x package-install angular-snippets

You can also install the dependencies on your own, and just dump
angular-snippets in your path somewhere:

 - <a href="https://github.com/magnars/s.el">s.el</a>
 - <a href="https://github.com/magnars/dash.el">dash.el</a>

## Usage

Right now there's only snippets for `html-mode` (mirrored into
`web-mode`) for the `ng-*` attribute directives. They all expand from `ng`.

Something slightly cool is that you get a short message with docs when
you expand a directive. You can also use `ng-snip-show-docs-at-point`
to show documentation for the closest `ng-*` directive. I have it on
`C-c C-d`. Pressing it again within 10 seconds opens the relevant
documentation in your browser.

## Setup

Well, you'll have to require it. You'll also need
[yasnippets](https://github.com/capitaomorte/yasnippet) of course
(sorry about the insult if that wasn't obvious, but dude, you had it
coming).

    (require 'angular-snippets)

I would also recommend adding `ng-snip-show-docs-at-point` to get that
nice documentation lookup thingie. Maybe something along the lines of:

    (eval-after-load "sgml-mode"
      '(define-key html-mode-map (kbd "C-c C-d") 'ng-snip-show-docs-at-point))

## Todo

The sky is the limit. There is lots room in AngularJS for awesome tooling
support, but this package isn't that. Not yet, at least. I'm adding to
it as I go along. Join me if you want.

## License

Copyright (C) 2013 Magnar Sveen

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
