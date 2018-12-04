# htmltagwrap #

[![Build Status](https://travis-ci.com/jcs090218/htmltagwrap.svg?branch=master)](https://travis-ci.com/jcs090218/htmltagwrap)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Wraps a chunk of HTML code in tags.<br/><br/>


## Configurations ##
The default tag is `p`, by setting `htmltagwrap-tag` you can change the
default tag to something else you want.
```
(setq htmltagwrap-tag "p")
```


## Key Bindings ##
This plugin does not have a default keybindings, just simply binds
`htmltagwrap-tag-wrap` function to the keymap you want.
```
(define-key global-map (kbd "M-w") #htmltagwrap-tag-wrap)
```


## Screenshot ##
<img src="./screenshot/htmltagwrap-demo.gif" width="600" height="203"/>


## Contribution ##
If you would like to contribute to this project. You may either
clone and make pull request to this repository. Or you can
clone the project and make your own branch of this tool. Any
methods are welcome!