#Introduction

This plugin is intended to those moments in vim where you are editing a file that belongs to a path not created yet.

#USAGE

Just install the plugin and when you open a file using vim and the file has some dir not created                                                  
the plugin will ask you what to do.                                                                                                               
Example in bash:                                                                                                                                  
```bash                                                                                                                                           
vim ./this/part/of/the/path/does/not/exist/file.txt                                                                                               
```                                                                                                                                               

Vim will prompt you if you want to create or not those dirs, tipping 'C' you will agree with the creation, while 'Q'
will cancel the action.

When you agree, vim will create every dir at once.

The same happens when you try to open a file using :e of vim.  
