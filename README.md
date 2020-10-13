

## Options

You can set these variables to any non-empty str in your `.zshrc`, so as to enable showing these optional prompt information.

~~~bash
agnoster_time=1                # show time
agnoster_env=1                 # show conda/virtualenv environment
agnoster_newline=1             # input in a new line
~~~

set options to `’'` to disable them, like

~~~bash
agnoster_time=''               # don't show time
~~~

options take effect after `antigen apply`.


## update theme

every time when you edit `*.zsh-theme` in this repo, please run `antigen reset` and login in another shell so as to preview the modified theme.

