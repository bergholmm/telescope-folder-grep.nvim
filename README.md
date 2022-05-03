# telescope-folder-grep.nvim

A telescope extension for selecting folders to perform `live_grep` search in.

## Installation

```vim
Plug 'nvim-lua/plenary.nvim'
Plug 'nvim-telescope/telescope.nvim'
Plug 'bergholmm/telescope-folder-grep.nvim'
```

## Setup

You can setup the extension by adding the following to your configuration:

```lua
require'telescope'.load_extension('folder_grep')
```

## Using:

```vim
:Telescope folder_grep
```

