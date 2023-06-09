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
