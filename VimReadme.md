### How to Open Vim
vim filename.txt

## Open Vim without a filename
vim

## Understanding Vim Modes
Vim has three main modes:

Normal mode ->	Navigate and run commands ->	Press Esc
Insert mode ->	Type and edit text	-> Press i, a, or o
Command-line ->	Save, quit, search, etc ->	Press : from Normal modes

## Basic Editing Commands

Enter Insert mode ->	i
Append after cursor->	a
Open new line below->	o
Delete line->       	dd
Undo->               	u
Redo->              	Ctrl + r
Copy line->         	yy
Paste->             	p
Search->            	/text
Replace->           	:%s/old/new/g

## Saving and Exiting
From **Normal mode**, press : to enter Command-line mode:

:w —> Save

:q —> Quit

:wq or :x —> Save and quit

:q! —> Quit without saving

ZZ —> Save and quit (shortcut)

ZQ —> Quit without saving (shortcut)

## [Navigation Commands]


- Left/Right/Up/Down ->	h, l, k, j
Start of line ->     	0
End of line->       	$
Next word->         	w
Previous word->     	b
Jump to line->      	:10 (line 10)

## Advanced Features

*Macros*: Record with qa, stop with q, play with @a

*Visual Mode*: Select text with v, then yank (y) or delete (d)

*Split Windows*: :split filename, :vsplit filename

*Tabs*: :tabnew filename, :tabnext, :tabclose

