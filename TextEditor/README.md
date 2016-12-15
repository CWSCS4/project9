# TextEditor

Files appear in top bar, separated by `|`. The current file's name has `*` characters around it.
Pressing most keys results in entering the character. Here are the special keys:
- `@`: Run a command to control the editor. Enter one of the following commands and press `ENTER`:
	- `N`: Open a new file
	- `R`: Rename current file
	- `W`: Close current file (data will be permanently lost)
	- `S`: Switch to a different file. Use left and right arrows to select the file, and then press `ENTER` when you are on the desired file. (will quit immediately if fewer than two files are open)
	- `H`: Show the list of commands. Press a key to return to the file.
- `\`: Press the key for the character you want to insert. This is useful for inserting any of the special characters (i.e. `@`, `\`, the backtick, or `~`)
- The backtick (`): Indent the current line two spaces
- `~`: Unindent the current line two spaces (if possible)
- Arrows: navigate around the file (up and down for switching between lines, left and right for moving along the line (or switching lines if at the beginning or end of the line))
- `BACKSPACE`: Does what you'd expect
- `ENTER`: Put the rest of the current line on a new line below, keeping the same indentation
- `HOME` and `END`: Go to the beginning or end of the current line