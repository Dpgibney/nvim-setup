# For installing the latest version of neovim on ubunut
'''
sudo snap install nvim --classic
'''

#For getting LazyVim (From www.lazyvim.org/installation)
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}

git clone https://github.com/LazyVim/starter ~/.config/nvim

rm -rf ~/.config/nvim/.git

#Load nvim
nvim

#If you're missing characters go to nerdfont and download a nerdfont
#I Like the JetBrainsMono font
#Extract the font to ~/.local/share/fonts
#Run

fc-cache -f -v to update the fonts

#Select the font in the terminal by right clicking the terminal -> preferences -> custom font
