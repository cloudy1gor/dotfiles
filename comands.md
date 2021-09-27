## Arch (Manjaro Sway) linux basic comands after install

sudo -Syy

sudo -Syu

sudo pacman -S git

pacman -S --needed git base-devel

git clone https://aur.archlinux.org/yay.git

cd yay

makepkg -si

sudo pacman -S kitty fish thunar ranger neofetch neovim

chsh -s /usr/bin/fish

git clone https://aur.archlinux.org/visual-studio-code-bin.git

cd visual-studio-code-bin/

makepkg -si

git clone https://aur.archlinux.org/sublime-text-4.git

cd sublime-text-4/

makepkg -si

git clone https://aur.archlinux.org/google-chrome.git

cd google-chrome/

makepkg -si

sudo pacman -S telegram-desktop discord flameshot vlc variety

sudo pacman -S nodejs npm yarn

sudo npm install --global typescript