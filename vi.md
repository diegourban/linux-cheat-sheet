# vi commands

## normal mode
* `directional arrows` - move the cursor around
* `0` - move the cursor the first character of the current line
* `$ (shift + 4)` - move the cursor to the last character of the current line
* `G (shift + g)` - move the cursor to the last line
* `1 G (shift + g)` - move the cursor to the first line
* `x` - remove the current character
* `12 x` - remove the next 12 characters
* `dd` - remove the current line
* `5 dd` - remove the next 5 lines
* `yy` - copy the current line to clipboard
* `3 yy` - copy the 3 lines to clipboard
* `p` - paste the content of the clipboard
* `10 p` - paste 10 times the content of the clipboard
* `:q` - exit
* `:w` - write changes

## other modes
* `i` - enter in insert mode, on the current cursor
* `a` - enter in append mode, after the current cursor
* `A (shift + a)` - enter in append mode, after the current line
* `/` - enter in search mode
 * type something to search for, example: `/textToFind`
 * `ENTER` - make the search
 * `n` - navigate to the next occurrance of the search
 * `N (shift + n)` - navigate to the previous occurrence of the search
* `ESC` - return to normal mode
