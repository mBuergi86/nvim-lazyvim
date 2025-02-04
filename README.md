# 🚀 My LazyVim Configuration

This repository contains my **personal LazyVim setup**, including **plugin configurations, themes, and language support**.

## 📦 Features
- ⚡ **Fast & optimized** Neovim setup using [LazyVim](https://github.com/LazyVim/LazyVim)
- 🎨 **Custom UI enhancements** (Lualine, Bufferline, Treesitter Context, Edgy)
- 🔍 **Better navigation & search** (FZF, Telescope, Snacks Picker)
- 🖊 **Code completion & linting** (nvim-cmp, Codeium, Mini plugins)
- 🛠 **Formatter & Linters** (Prettier, ESLint, Conform.nvim, None-ls)
- 🧑‍💻 **LSP & Debugging** (nvim-lspconfig, DAP, Mason)
- 📑 **Language support** (Go, TypeScript, YAML, SQL, Markdown, C# via OmniSharp)

---

## 🔌 Installed Plugins
Here are some of the **main plugins** included:

### 🔹 **Code Editing**
- `nvim-cmp` - Autocompletion
- `yanky.nvim` - Better Yank/Paste
- `mini.surround` - Surround text manipulation
- `vim-dadbod-ui` - SQL Database UI

### 🎨 **User Interface**
- `lualine.nvim` - Custom Status Line
- `bufferline.nvim` - Tab management
- `neo-tree.nvim` - File Explorer
- `indent-blankline.nvim` - Indentation guides

### 🔍 **Search & Navigation**
- `fzf-lua` - FZF picker (alternative to Telescope)
- `telescope.nvim` - Fuzzy Finder
- `snacks.nvim` - Fast and modern file picker

### 🛠 **Development Tools**
- `nvim-lspconfig` - Language Server Protocol (LSP)
- `nvim-dap` - Debug Adapter Protocol (DAP)
- `conform.nvim` - Code Formatter
- `none-ls.nvim` - Additional linters & formatters

### 🏗 **Project Management & Utilities**
- `chezmoi.nvim` - Manage dotfiles
- `project.nvim` - Project switching
- `dashboard-nvim` - Start screen

---

## 📜 Supported Languages
This setup includes **LSP, formatters, and linters** for:

- **Go** (`neotest-golang`, `nvim-dap-go`, `nvim-lspconfig`)
- **TypeScript / JavaScript** (`mason.nvim`, `nvim-lspconfig`, `nvim-dap`)
- **SQL** (`vim-dadbod`, `vim-dadbod-completion`, `vim-dadbod-ui`)
- **YAML** (`SchemaStore.nvim`, `nvim-lspconfig`)
- **Markdown** (`markdown-preview.nvim`, `nvim-lspconfig`)
- **C# / .NET** (`OmniSharp`, `neotest-dotnet`, `nvim-dap`)
- **Docker** (`nvim-lspconfig`, `none-ls.nvim`, `nvim-lint`)
- **Zig** (`neotest-zig`, `nvim-lspconfig`)
- **Svelte & TailwindCSS** (`nvim-lspconfig`, `tailwindcss-colorizer-cmp`)

---

## 🛠 Installation
Clone this repository into your **Neovim config directory**:
```sh
git clone https://github.com/mBuergi86/nvim-lazyvim.git ~/.config/nvim
```
Then start Neovim and **LazyVim** will handle the rest:
```sh
nvim
```
To update all plugins:
```sh
Lazy sync
```

---

## 📌 Notes
- This setup is designed for **Neovim 0.9+**
- Some features require **Mason** (`MasonInstall`)
- Debugging requires **nvim-dap** and appropriate adapters
---

## 🙌 Contributing
Feel free to open **issues or pull requests** if you have improvements!
