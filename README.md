# Lazy-neovim-config

This is my custom config of Neovim which is primarily optimized for my workflow but can be configured for any other workflow without a hassle.

## Features configured

- catppuccin theme - A beatiful dark theme with syntax highight support.
- lualine - A theme for the neovim bottom info bar.
- telescope - for fuzzy searching and greping through files.
- treesitter - for advanced syntax highlighting with automatic language detection.
- neo-tree - A file tree sidebar for easy file management in projects.
- lspconfig, None-ls, cmp-nvim-lsp, luasnip and friendly-snippets - To provide code snippets and suggestions.
- nvim-dap and nvim-dap-ui - for debugging (work in progress) _basic setup has been done_.

## Prerequisites

- Linux, MacOS or Windows system
- A true color supported terminal (eg: iTerm2, Alacritty, Kitty and etc.)
- A Nerd font installed and enabled for your terminal. Get one from here -> https://www.nerdfonts.com/
- RipGrep - A supporting application for enabling Greping capabilities. (https://github.com/BurntSushi/ripgrep)

## How to use this config

1. Install Neovim (if you haven't already).
2. Pull the config from my repo using git.
    - You should put the these files in the neovim's default runtime path which is ~/.config/nvim/init.lua (Pull the files directly to there or copy after downloading).
3. Open neovim using nvim command and source the init.lua file.
    - You can source the init.lua file by openning that file directly from neovim and running :Source % in the neovim command pallete.
4. Now run :Lazy in neovim command pallete and lazy.nvim will install all the nessary plugins.


## Credits

- Neovim
- catppuccin
- lualine
- telescope
- treesitter
- neo-tree
- lspconifg
- None-ls
- cmp-nvim-lsp
- luasnip
- friendly-snippets
- nvim-dap
- nvim-dap-ui
- Ripgrep
- MesloLGS NF (Nerd Font)
- iTerm2

## Thank You ❤️

Thank you for reading till the very end. Happy coding N3RDS!
