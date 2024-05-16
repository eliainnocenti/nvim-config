# Neovim configuration

This repository contains my personal Neovim configuration files, including plugins, key mappings, and settings.

### Installation

To use this configuration, you'll need to have Neovim installed on your system. If you haven't already installed Neovim, you can find instructions on how to do so on the [Neovim website](https://neovim.io/).

Once Neovim is installed, you can clone this repository to your local machine:

```bash
git clone https://github.com/username/nvim-config.git ~/.config/nvim
```

This will clone the repository into your Neovim configuration directory (~/.config/nvim).

### Features

- **Custom Key Mappings**: improved key mappings for more efficient editing.
- **Plugin Management**: plugins are managed using [lazy](https://github.com/folke/lazy.nvim)
- **LSP Integration**: Language Server Protocol integration for code intelligence.
- **Custom Theme**: custom color scheme for a personalized editing experience.

### Plugins

- [Alpha](./lua/elia/plugins/alpha.lua): to enhance Neovim's user interface.
- [Auto Session](./lua/elia/plugins/auto-session.lua): to manage work sessions automatically.
- [Auto Pairs](./lua/elia/plugins/autopairs.lua): for automatic bracket and closing character completion.
- [Bufferline](./lua/elia/plugins/bufferline.lua): to manage buffer tabs in Neovim.
- [Colorscheme](./lua/elia/plugins/colorscheme.lua): for managing color schemes.
- [Comment](./lua/elia/plugins/comment.lua): to simplify code commenting and uncommenting.
- [Dressing](./lua/elia/plugins/dressing.lua): for adding decorations and aesthetic customizations.
- [Formatting](./lua/elia/plugins/formatting.lua): for automatic code formatting.
- [Gitsigns](./lua/elia/plugins/gitsigns.lua): to display Git file status within Neovim.
- [Indent Blankline](./lua/elia/plugins/indent-blankline.lua): to display indented blank lines in code.
- [Lazy Git](./lua/elia/plugins/lazygit.lua): to integrate Git directly into Neovim.
- [Linting](./lua/elia/plugins/linting.lua): for syntax checking and code style enforcement.
- [LSP Config](./lua/elia/plugins/lsp/lspconfig.lua): for configuring the Language Server Protocol in Neovim.
- [LSP Mason](./lua/elia/plugins/lsp/mason.lua): to enhance support for certain languages via the Language Server Protocol.
- [Lualine](./lua/elia/plugins/lualine.lua): for customizing Neovim's status line.
- [nvim-cmp](./lua/elia/plugins/nvim-cmp.lua): for advanced auto-completion in Neovim.
- [nvim-tree](./lua/elia/plugins/nvim-tree.lua): for file system exploration within Neovim.
- [Substitute](./lua/elia/plugins/substitute.lua): to simplify text substitution.
- [Surround](./lua/elia/plugins/surround.lua): to add and remove delimiters around selected text.
- [Telescope](./lua/elia/plugins/telescope.lua): for file search and navigation in Neovim.
- [Todo Comments](./lua/elia/plugins/todo-comments.lua): for displaying and managing TODO comments in code.
- [Treesitter](./lua/elia/plugins/treesitter.lua): for integrating Treesitter into Neovim for advanced syntax recognition.
- [Trouble](./lua/elia/plugins/trouble.lua): to simplify error and trouble management in Neovim.
- [Vim Maximizer](./lua/elia/plugins/vim-maximizer.lua): to maximize the current window in Neovim.
- [Which Key](./lua/elia/plugins/which-key.lua): for displaying key bindings in Neovim.

### References

- [Josean Martinez - Neovim configuration repo](https://github.com/josean-dev/dev-environment-files)
- [Josean Martinez - Neovim configuration tutorial](https://www.youtube.com/watch?v=6pAG3BHurdM&list=PL-v7YW_oIxenimA8DCSklWnZHuIm5JpqH&index=6)
