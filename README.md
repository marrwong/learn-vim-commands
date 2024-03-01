# Learn Vim Commands Through Hands-on Practice

This repository contains a list of keybindings that I've used in Vim.

## Getting Started

Clone the repo, then run the following:

`vim README.md`

This will take you into the vim editor (visual mode). As you read the document, use the keys to practice on the document.

## Navigating the Document with the Cursor

`h` `j` `k` `l` - Use these keys for navigating **left, down, up, and right** respectively.

(One way of using mnemonics to recall this:
`h` is on the left of the group of 4 letters, while `l` is on the right. Up is beside right, because its the only pair that forms a word (upright).)

`w` - **Moves the cursor to the start of the next word.**

(Try to navigate to the end of this line using `w`.)

`e` - **Moves the cursor to the end of the next word.**

(It helps that `e` is to the right of `w` on the keyboard.)

`b` - **Moves the cursor back** to the start of the previous word.

(As always, you can practice navigating through this file using the keys you have just learnt.)

`#` or `0` - **Moves the cursor to the start of the line.**

(Personally, I prefer to use `#` as it is right beside `$`, which complements `#` in function.

`$` - **Moves the cursor to the end of the line.**

`H` - **Moves the cursor to the top of the screen.**

`M` - **Moves the cursor to the middle of the screen.**

`L` - **Moves the cursor to the bottom of the screen.**

`%` - **Moves the cursor to the next matching {[( )]}**

(Try to move the cursor to the closing parenthesis at the end of this line!)

`gg` - **Moves the cursor to the start of the file.**

(good game, let's start over again!)

`G` - **Moves the cursor to the end of the file.**

(Goodness, Gracious, Gonna have to use the shift key too!)

## Text manipulation

`dd`

`yy`

`p`

## Insert mode

`o` - **Inserts a new line**

`Esc` - **Exit insert mode**. Goes back to visual mode.

## Command mode

To enter the command mode, type the colon (`:`) key. The colon should appear at the bottom left of the terminal, where you will type the commands.

`:w` - **Writes changes to disk i.e. saves the file.** This is usually used with `q` i.e `:wq` to save and quit.

`:q!` - **Quits without saving changes**

`:x` - **Quits and writes changes to disk, if there are any**

(This is a bit too ambiguous for my liking and not worth the one less keystroke that you save.)

## Searching for text

`/` - **Enter search mode**. The `/` character will appear at the bottom of the file. Key in the search term, then press **enter** to search.

`n` - **Find the next match** starting from the cursor position

`N` - **Find the previous match**.
