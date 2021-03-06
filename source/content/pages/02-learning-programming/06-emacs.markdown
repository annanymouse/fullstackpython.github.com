title: Emacs
category: page
slug: emacs
sort-order: 0206
meta: Emacs is an extensible, customizable text editor often used for coding. Learn more about Emacs on Full Stack Python.
choice1url: /vim.html
choice1icon: fa-file-text
choice1text: Tell me more about Vim, another powerful text editor.
choice2url: /best-python-resources.html
choice2icon: fa-book fa-inverse
choice2text: Show me a list of the best Python learning resources.
choice3url: /web-frameworks.html
choice3icon: fa-code fa-inverse
choice3text: I want to get started coding a Python web app.
choice4url:
choice4icon:
choice4text:


# Emacs
Emacs is an extensible text editor that can be customized by writing Lisp
code.


## Why is Emacs a good choice for Python coding?
Emacs is designed to be customized via the built-in Lisp interpreter and
package manager. The package manager, named package.el, has menus for
handling installation. The largest Lisp Package Archive is 
[Melpa](http://melpa.org), which provides automatic updates from upstream
sources.

Macros are useful for performing repetitive actions in Emacs. A macro
is just a recording of a previous set of keystrokes that can be replayed
to perform future actions.

Hooks, which are Lisp variables that hold lists of functions to call,
provide an extension mechanism for Emacs. For example,
``kill-emacs-hook`` runs before exiting Emacs so functions can be loaded
into that hook to perform necessary actions before the exiting completes.


## General Emacs resources
* [GNU Emacs Manual](http://www.gnu.org/software/emacs/manual/html_node/emacs/index.html)
  provides an official in-depth review for how to use Emacs.

* [Emacs Redux](http://emacsredux.com/) is a blog with tips and tricks for
  how to use Emacs effectively.

* [Emacs Rocks](http://emacsrocks.com/) is a video tutorial series for Emacs.

* [What the .emacs.d?!](http://whattheemacsd.com/) provides a bunch of tiny
  optimizations for Emacs' workflow.


## Notable Elisp Packages
* [Magit](http://magit.github.io/) allows the user to inspect and modify
  Git repositories from within Emacs.

* [company-mode](http://company-mode.github.io/) creates a modular in-buffer
  completion framework.

* [Flycheck](http://flycheck.github.io/) provides syntax checking.

* [anaconda-mode](https://github.com/proofit404/anaconda-mode/) is specific
  to Python development and allows code navigation, documentation lookup 
  and code completion. The [jedi](http://jedi.jedidjah.ch/en/latest/) library 
  is used under the hood.

* [Tern](http://ternjs.net/) is a stand-alone code-analysis engine for
  JavaScript. It can be integrated within a Django project
  via the [tern-django](https://github.com/proofit404/tern-django) package.


## Popular user configurations
* [Prelude](https://github.com/bbatsov/prelude) is an enhanced Emacs
  version 24 distribution.

* [A reasonable Emacs config](https://github.com/purcell/emacs.d) shows
  a batteries-includes Emacs configuration bundle.

* [Emacs settings](https://github.com/magnars/.emacs.d) is a repository of
  configurations used in the Emacs Rocks screencasts.

* [Spacemacs](https://github.com/syl20bnr/spacemacs) mashes together Emacs'
  extensibility and Vim's ergonomic text editing features.


### What's next once your development environment is set up?
