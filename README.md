# nvim-configs
Here, you can find how I prefer to organize my text/code editor: Nvim. Using vim-plug as a Plugin Manager for nvim, I use several plugins to make my environment more efficient, such as: coc.nvim, vim-commentary, vim-surround and many more.

## Preparing the environment

- first of all, you need to have `nvim` installed in your Linux. If you don't have it in your machine, you can install it through the following script:
```sudo apt install neovim```

- after that, you need to install a plugin manager for nvim. I use `vim-plug` for that purpose. If you want to install it in your machine, you can do it following the command below:
``curl -fLo ~/.var/app/io.neovim.nvim/data/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim``
  - in case this command doesn't work, you might have to install `curl`. for that, you run: `sudo apt install curl`.

- then, you can clone this repository into your machine. the easiest way to configure your environment is to clone this repository directly in the folder: `~/.config/nvim/` (in case this folder doesn`t exists, you shall create it).

