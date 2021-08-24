Conf:
At beginning https://nvchad.netlify.app/getting-started/setup/

:PackerInstall
:PackerSync

Get ripgrep maybe conf it
Get elixir-ls and add those line to the lspconfig.lua

-- Elixir
require'lspconfig'.elixirls.setup{
  cmd = { vim.loop.os_homedir().."/.config/elixir-ls/language_server.sh" };
}

verify all works with <space> th for theme or :Rg <anything> for search with fzf
