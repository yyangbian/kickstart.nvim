## Useful command
- `:Telescope keymaps`: to search for keymaps.
- `:Telescope help_tags`: to search all help information.
- `:help lualine.txt` to read through the plugin help document.
  - `:help telescope`, `:help telescope.setup`, `:help telescope.builtin`
- `:Mason` to list all supported lsp. Select and press `i` to install.
  - Or use `:MasonInstall`


## Keymaps
| Key map  | Function |
| ------------- | ------------- |
| `<leader>?`  | Find recently opened file  |
| `<leader><space>`  | Find existing buffers  |
| `<leader>/`  | Fuzzily search in current buffer  |
| `<leader>sf`  | [S]earch [F]ile |
| `<leader>sh`  | [S]earch [H]elp |
| `<leader>sw`  | [S]earch current [W]elp |
| `<leader>sg`  | [S]earch by [G]rep |
| `<leader>sd`  | [S]earch [D]iagnostics |

### Keymaps provided by tree-sitter
TODO -- need to fill the rest
| Key map  | Function |
| ------------- | ------------- |
| `<ctrl-space>`  | Select current or bigger syntatic block  |
| `<ctrl-backspace>`  | Select the next smaller syntatic block |
| `]m`  | move to the start of next function |
| `[m`  | move to the start of previous function |
| `]]`  | move to the start of next class |
| `][`  | move to the end of next class |
| `]M`  | move to the end of next function |
| `[d`  | go to previous diagnostic |
| `]d`  | go to next diagnostic |
| `<leader>e`  | open diagnositc float |
| `<leader>q`  | ??? |

### Keymaps provided by lsp
| Key map  | Function |
| ------------- | ------------- |
| `<leader>rn`  | ReName  |
| `<leader>ca`  | Code Action  |
| `gd`  | Goto Definition  |
| `gr`  | Goto Reference  |
| `gI`  | Goto Implementation  |
