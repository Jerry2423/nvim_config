## Neovim Configuration

**General Notes**
- In terminal, enter `cd ~/.config/nvim` to setup the plugins and other configurations.
- Add plugins:
1. `cd ~/.config/nvim/lua/user/plugins-setup.lua`: add the code and use `:w` to save files and file will download plugins automatically. Don't use `:wq`, this won't work.
2. Create the plugin configuration file `pluginname.lua` under the directory '~/.config/nvim/lua/user/'
3. Add the plugin in the `init.lua`

**Updates**
- Toggleterminal: `ctrl-t`

**LSP Management**

- Go to the `lua/user/lsp`
- Enter `:Mason`
- Enter `/[language]`
- Go to the language and enter `i` to install
- Open the `mason.lua` file, and add the language to `local_server_lists`
- Save `mason.lua` and done!



**Treesitter Highlighting**

- [Language parser and setup](https://github.com/nvim-treesitter/nvim-treesitter#folding)

- [Code folding(tree sitter-based)](https://alpha2phi.medium.com/neovim-for-beginners-code-folding-7574925412ea)

- [Code folding command](https://stackoverflow.com/questions/2362914/fold-function-in-vim)
