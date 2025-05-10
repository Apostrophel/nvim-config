# My personal NvChad/Neovim Configuration Files
This is my first attempt to store my changes of my config files.

## Current changes

### Mappings.lua
In mappings the `<Esc>` key is bound to the command for exiting the terminal mode when it is activated:
```lua
-- Terminal mode mapping - Method 1
map("t", "<Esc>", "<C-\\><C-n>", { noremap = true, silent = true })
```


## Original README Content
**This repo is supposed to used as config by NvChad users!**

- The main nvchad repo (NvChad/NvChad) is used as a plugin by this repo.
- So you just import its modules , like `require "nvchad.options" , require "nvchad.mappings"`
- So you can delete the .git from this repo ( when you clone it locally ) or fork it :)

### Credits

1) Lazyvim starter https://github.com/LazyVim/starter as nvchad's starter was inspired by Lazyvim's . It made a lot of things easier!
