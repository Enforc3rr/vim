# vim

### To close vim :
- Press `:` 
- Followed by `q`
Let's say we have made any changes to the vim , it won't allow us to quite . Inorder to quite at that moment , we will either have to write those changes by saying `:w` then type `:q` or we can simply type `:wq` .

To forcefully close vim without any changes , we can simply type `:q!` and not `:!q` or anything else.
Basically pressing `:!` is a terminal command . So , typing `!ls` wil exec `ls` command .



### On Start : [press `esc` in insert mode to enter normal mode]
- As soon as we start vim , we're in a normal and every key in this mode acts as a command.
- `:` to execute a command.
- `i` to enter insert mode and it inserts before the cursor.
- `shift + i`enters insert mode at start of that line.
- `a` to enter insert mode and it inserts after the cursor.
- `shift + a`enters insert mode at end of that line.
- `o` to enter insert mode but it creates a new line.
- `shift + o`enters insert mode above that line.
- `h`,`j`,`k`,`l` : can be used to replace functionality of the arrow keys.


### Customising vim : [to permanently set custom settings : change `~/.vimrc`]
- `:set number` : to get line numbers on left.
- `:set relativenumber` : to get relative line numbers.
- `:set mouse=a`: to be able to use mouse.
- `:colorscheme` + tab_key to select the required color scheme.
- `:set tabstop=4`
- `set autoindent`

### Useful shortcuts :
- `u` : undo's the action in normal mode as file was in last normal mode.[ we can combine it with numbers ]
- `ctrl+r` : redo the action in normal mode.
- `v` in normal mode goes takes us to visual mode.
- we can select words or letters using arrows
  - To delete press `d` , `d`+`d` deletes a line. 
  - To copy press `y` , `y`+`y` copies a line.
  - To paste press `p`.


