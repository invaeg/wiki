# vim kick start
### vim is a text editor which run in terminal, that means it doesn't need any desktop environment
### vim program while running can be in one of 3 modes.

1. **Command mode**
1. **Insert mode**
1. **Visual mode (not covered in this tutorial)**


#### Running vim editor:

vim config.txt

Above command will open config.txt file if it exists or open a new file.<br />
vim always start in **command mode**, in this mode you can, exit from vim, save file, or goto other modes.<br />
Also from any mode if you press **esc** then you'll be back to command mode.

#### Editing file:

To edit file vim should be in **insert mode** from command mode.<br />
Press **i** to goto insert mode.<br />
Once you are in insert mode, you can move cursor to disired place and edit text.<br />

#### Exiting from vim:

Once you're done with the editing you might want to close vim editor, with or witout saving file.<br />
##### Exit vim with saving file
1. Press **esc** just to make sure you are in command mode.
1. Type **:wq**
1. Hit enter

**w** stands for write and **q** stands for quit.

##### Exit vim without saving file
1. Press **esc** just to make sure you are in command mode.
1. Type **:q**
1. Hit enter

You might get an error here if you did some editing after opening the file.<br />
If you are sure that you don't want to save your change then type below in command mode:<br />
**:q!**

### These are enough commands to get stated with vim, rest you'll learn more as per your need ###
#### Happy vim-ing :smile: ####
