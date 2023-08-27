## My Neovim Configuration

This repository contains my personal configuration for Neovim. This setup aims to optimize the workflow for coding by providing a highly customized and feature-rich environment.

## Features

* Line Numbering: Enables line number display.
* Plugin Management: Utilizes packer.nvim for plugin management.
* Syntax Highlighting: Uses nvim-treesitter for enhanced syntax highlighting and code navigation.
* Discord Presence: Uses presence.nvim to display what you are editing on Discord.
* Theme: Utilizes the tokyonight.nvim theme.
* GitHub Copilot: Support for GitHub's Copilot for autocompleting and suggesting code.
* Minimal LSP Setup: Uses lsp-zero.nvim along with other dependencies to provide a minimal Language Server Protocol (LSP) environment.
* Autocompletion: Utilizes nvim-cmp along with several other plugins to provide autocompletion functionality.
* Snippets: Support for snippets via LuaSnip and friendly-snippets.
  
## Requirements

* Neovim >= 0.5
* packer.nvim for plugin management.
* git to clone some of the plugins.

## Installation

1. Make sure you have Neovim 0.5 or higher installed.
2. Clone this repository into your Neovim configuration directory. This is usually ~/.config/nvim.

```bash
git clone https://github.com/alvarorichard/Neovim.git
cd Neovim
```

Open Neovim and run the following command to install packer.nvim if you haven't already:

```bash
:PackerInstall
```
This will install all the plugins.

To update all the plugins, you can run:

```vim
:PackerUpdate
```
## Usage

* The leader key is set to space (" ").
* Press <leader>pv to execute a specific Ex command (to be defined).
  
## Contributing

If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.