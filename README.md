# contextual-menubar

[![MELPA](https://melpa.org/packages/contextual-menubar-badge.svg)](https://melpa.org/#/contextual-menubar) [![MELPA Stable](https://stable.melpa.org/packages/contextual-menubar-badge.svg)](https://stable.melpa.org/#/contextual-menubar)


Displays the menubar if on a graphical display, but hides it if in a terminal.
It works for multiple frames on the same server.

Original code from Tyler Smith: http://emacs.stackexchange.com/questions/29441/how-do-i-disable-menu-bar-mode-only-for-tty-frames

## Installation

You can install this package from [Melpa][]

```
M-x package-install RET contextual-menubar RET
```

## Usage

Add to your `init.el`:

```elisp
(contextual-menubar-install)
```

[Melpa]: http://melpa.milkbox.net/
