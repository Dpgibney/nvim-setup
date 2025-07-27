# For installing the latest version of neovim on ubunut
```bash
sudo snap install nvim --classic
```

# For getting LazyVim (From www.lazyvim.org/installation)
Back up old config
```bash
mv ~/.config/nvim{,.bak}

mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

Get LazyVim
```bash
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf ~/.config/nvim/.git
```


#Load nvim
nvim

If you're missing characters go to nerdfont and download a nerdfont
I Like the JetBrainsMono font
Extract the font to ~/.local/share/fonts
Run

```bash
fc-cache -f -v to update the fonts
```

Select the font in the terminal by right clicking the terminal -> preferences -> custom font
