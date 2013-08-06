frame-restore.el
================

Save and restore position and size of the Emacs frame.

**Note:** Since [r113242][] the built-in Desktop Save mode will restore frames.
If you are using a Emacs snapshot build later than this revision, you are
**strongly** advised to use Desktop Save mode instead.  Frame Restore mode will
display a bold warning if enabled in an Emacs build whose Desktop Save mode
can restore frames.

[r113242]: http://bzr.savannah.gnu.org/lh/emacs/trunk/revision/113242

Installation
------------

Install the ELPA package from [MELPA][] or [Marmalade][] with `M-x
package-install RET frame-restore`, and add the following to your `init.el`:

```scheme
(frame-restore-mode)
```

Customization
-------------

`M-x customize-group RET frame-restore`

License
-------

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see http://www.gnu.org/licenses/.

See [COPYING][] for details.

[melpa]: http://melpa.milkbox.net
[marmalade]: http://marmalade-repo.org/
[copying]: https://github.com/lunaryorn/frame-restore.el/blob/master/COPYING
