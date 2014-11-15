# bats-mode

## Synopsis

`bats-mode` is an Emacs mode for editing and running [Bats tests](https://github.com/sstephenson/bats).

`bats-mode` derives from the bash flavor of `sh-mode`, adding font-lock for bats keywords.

## Installation

If you have a recent Emacs with `package.el`, you can install `bats-mode`
from [MELPA](http://melpa.org/).

Or manually add to your emacs `load-path`.

## Usage

### bats-run-all

Run bats in the current directory.

Keybinding: <kbd>C-c C-a</kbd>

### bats-run-current-file

Run bats with the current buffer file.

Keybinding: <kbd>C-c C-,</kbd>

### bats-run-current-test

Run bats with the current test at point.

Keybinding: <kbd>C-c M-,</kbd>

Note, this feature is not yet merged into a Bats release.
See the [github issue](https://github.com/sstephenson/bats/issues/36) for more info.
