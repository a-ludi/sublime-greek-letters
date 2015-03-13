Greek Letters for Sublime Text 2/3
==================================

This package Provides completion for greek letter in sublime Text 2/3. It
uses the exact same names as known from LaTeX's AMSmath. Just enter a the name of the desired letter (or parts of it) and press `<Tab>`.


Examples
--------

| Entered Text   |  Result  | Comment                          |
| :------------- | :------: | :------------------------------- |
| `tau<tab>`     |   `τ`    |                                  |
| `varphi<tab>`  |   `φ`    |                                  |
| `phi<tab>`     |   `ϕ`    |                                  |
| `epsilon<tab>` |   `ε`    |                                  |
| `eps<tab>`     |   `ε`    | you can use abbreviation as well |
| `vt<tab>`      |   `ϑ`    | … and again                      |


Installation
------------


### Package Control

The recommended way to install this package is to use [Package Control][1]. Just install Package Control, press `<Ctrl+Shift+P>`, choose `Package Control: Install Package` from the list and search for `GreekLetters`.

If you cannot find the package you can also add this repository manually by adding [https://github.com/a-ludi/sublime-greek-letters.git][2] as a Package Control repository. Repeat the steps from above afterwards.

### Git Clone

Clone this repository in to the Sublime Text 2 `Packages` directory, which
is located where ever the _Preferences_ → _Browse Packages_ option in
sublime takes you.

### Git Copy

Alternately, you can download a [copy of this package][3], rename the file to `GreekLetter.sublime-package` and move it to the `Installed Packages` directory which is located in the same directory as the `Packages` directory. Afterwards, restart sublime and your done.

[1]: https://packagecontrol.io/ "Package Control"
[2]: https://github.com/a-ludi/sublime-greek-letters.git "Greek Letters on GitHub"
[3]: https://github.com/a-ludi/sublime-greek-letters/archive/master.zip "ZIP-Archive of Greek Letters"


License
-------

Copyright © 2015 Arne Ludwig <arne.ludwig@posteo.de>.

This package is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This package is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
details.

You should have received a copy of the GNU General Public License along with
this package.  If not, see <http://www.gnu.org/licenses/>.
