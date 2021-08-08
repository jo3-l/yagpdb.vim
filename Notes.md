# Notes

This document is a comprehensive, but not exhaustive list of useful and helpful things.

## Resources

* [Learn Vim Script the Hard Way](https://learnvimscriptthehardway.stevelosh.com)

  An excellent resource walking through the rabbithole that Vim Script is. Also, chapters 41 and onward specifically cover plugin development.

* [Vim RegEx Reference](https://learnbyexample.gitbooks.io/vim-reference/content/Regular_Expressions.html)

* [genfuncdata.go](https://github.com/jo3-l/yagpdb/blob/master/stdcommands/genfuncdata/genfuncdata.go)

  A Go program used to auto-generate the yagpdb functions data for the [check-yag-tmpl-syntax action](https://github.com/jo3-l/action-check-yag-tmpl-syntax).

## Other

* Implement code folding. This can be based on:
  * Indentation (easy, less reliable)
  * Custom scripting (harder, more reliable, can be based on language feature like if/else/end blocks).
* Consider automating certain files such as [`syntax/yagpdb-cc.vim`](./syntax/yagpdb-cc.vim)
* Figure out a way to validate syntax - perhaps without the abuse of RegEx. Alternatively, RegEx.