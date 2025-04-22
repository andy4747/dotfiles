# andy4747's Dotfiles 🛠️

Welcome to my personal dotfiles repo! This is where I keep configuration files for my development environment, including Neovim, Tmux, Kitty, and Zsh. These dotfiles are setup just for my needs.

## ✨ Features

- **Neovim**: Modular Lua configuration with LSP, Treesitter, Telescope, Neo-Tree and Tmux navigation support.
- **Tmux**: Minimalist statusline, vim-like keybindings, and custom window switching.
- **Kitty Terminal**: my config for kitty terminal.
- **Zsh**: my ~/.zshrc file with all my configs.

## 🗂 Structure

```
.
├── .config
│   ├── kitty
│   │   └── kitty.conf
│   └── nvim
│       ├── init.lua
│       ├── lua
│       │   └── andy4747
│       │       ├── core
│       │       │   ├── autocmds.lua
│       │       │   ├── keymaps.lua
│       │       │   └── options.lua
│       │       └── plugins
│       │           ├── editor.lua
│       │           ├── init.lua
│       │           ├── lsp.lua
│       │           ├── tools.lua
│       │           └── ui.lua
│       └── README.md
├── .gitconfig
├── README.md
├── scripts
│   ├── install_go_tools.sh
│   └── setup_github_ssh_linux.sh
└── .tmux.conf
```

## 🚀 Quick Setup

Clone the repository:

```bash
git clone https://github.com/andy4747/dotfiles.git ~/dotfiles
cd ~/dotfiles
```

Then manually copy the files:

```bash
cp ~/dotfiles/zshrc ~/.zshrc
cp ~/dotfiles/tmux.conf ~/.tmux.conf
cp -r ~/dotfiles/nvim ~/.config/nvim
cp -r ~/dotfiles/kitty ~/.config/kitty
```

> Back up any existing configs before copying.

## 📸 Screenshots

Here are some screenshots showcasing my setup:

### Neovim in Action
Here are some screenshots showcasing my setup:
![Neovim](./docs/ss/neovim.png)
![Neovim](./docs/ss/neovim_source.png)

## 🔧 Dependencies

Mandatory Dependencies:

- Neovim 0.10+
- Tmux 3.2+
- Kitty terminal
- Zsh + a plugin manager ([oh-my-zsh](https://ohmyz.sh/))
- Fonts (FiraCode Nerd Font)

## 🙌 Credits

- Inspired by [ThePrimeagen](https://github.com/ThePrimeagen), [tjdevries](https://github.com/tjdevries), [
Seth Phaeno](https://www.youtube.com/@sethyedw), [Josean Martinez](https://www.youtube.com/@joseanmartinez), [Dreams of Code](https://www.youtube.com/@dreamsofcode) and the dotfiles community.
- Uses various open-source plugins and themes — check individual config folders for details.

## 📝 License

MIT — feel free to fork and adapt.

---

Made with ❤️ by [andy4747](https://codeangel.tech)
