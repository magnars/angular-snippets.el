# angular-snippets.el

Yasnippets for [AngularJS](http://angularjs.org/).

## Installation

If you haven't, install [yasnippet](http://capitaomorte.github.com/yasnippet/),
then dump angular-snippets.el into your load path somehow, and require it:

    (require 'angular-snippets)

That's it.

## Usage

Right now there's only snippets for `html-mode` (mirrored into
`web-mode`) for the `ng-*` attribute directives. They all expand from `ng`.

Something slightly cool is that you get a short message with docs when you
expand a directive.

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
