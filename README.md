# lua-plugins
neovim lua plugins configuration

init.lua file:

```lua
-- bootstrap lazy.nvim, LazyVim and your plugins
require("config.lazy")

vim.o.background = "dark" -- or "light" for light mode
vim.cmd([[colorscheme gruvbox]])
```
