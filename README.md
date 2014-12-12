# promela-mode.el

Slightly modified version of promela-mode.el (see
http://spinroot.com/spin/Src/promela-mode.el) to work with Emacs 24.

Tested with Emacs 24.4. 

## Setup

```elisp
(add-to-list 'load-path "~/PATH/promela-mode") ; location where you cloned promela-mode
(require 'promela-mode)
(add-to-list 'auto-mode-alist '("\\.pml\\'" . promela-mode))
```
