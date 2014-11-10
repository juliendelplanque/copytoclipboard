Copy to Clipboard
===============

A small tool to copy things from the command line to the clipboard.

###Installation:

* Install *pyperclip*

~~~
$ pip install pyperlip
~~~

* Clone this repository
* Add the repository to your path in your ~/.bashrc or ~/.zshrc:

~~~
export PATH="$PATH:/path/to/copytoclipboard"
~~~

Enjoy!

###Examples:

~~~
$ ctc -i "This will be in the clipboard."
~~~

~~~
$ lspci | ctc # The result of lspci will be in the clipboard.
$ ctc -p # Will output the content of the clipboard.
~~~