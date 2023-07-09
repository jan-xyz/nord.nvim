# nord.nvim

Direct Lua port of [nordtheme/vim](https://github.com/nordtheme/vim) with no bloat. Only the pure theme.

## Goal

* Keep the simplicity of Nord and don't do fancy things.
* Keep compatible with latest version of Neovim
* Provide sane defaults

## Installation

Lazy

```lua
	{
		"jan-xyz/nord.nvim",
	}
```

Packer

```lua
packer.use({
		"jan-xyz/nord.nvim",
	})
```

Set it with

```lua
vim.cmd("colorscheme nord")
```
