# zzt-to-js
A ZZT-OOP to JavaScript compiler (wip). Based off the Medium article by Mariko Kosaka: https://medium.com/@kosamari/how-to-be-a-compiler-make-a-compiler-with-javascript-4a8a13d473b4#.r0xwt0h76.
This is a side project I decided to do for fun, so any pull requests or issues opened are greatly appreciated!

[Demo](http://liamdebeasi.com/compiler/) | [ZZT-OOP Documentation](http://apocalyptech.com/linux/zzt/manual/langref.html)

## Supported Commands

This is very much a work in progress, so not all commands are supported.

### #GIVE [item] [count]
Gives an item of a specified amount to the player.
Example: #GIVE GEMS 10

### #TAKE [item] [count] [message]
Takes an item of a specified amount from the player. If the player does not have enough of that item, a message will be shown.
Note: The message option is not currently supported.
Example: #TAKE GEMS 10

### #DIE
Kills the player.
Example: #DIE

### $[text]
Displays a single line of text centered and at the top of the screen.
Example: $Hello World!

### [text]
Displays a block of text in a modal
Example: Hello World! This should be displayed in a modal