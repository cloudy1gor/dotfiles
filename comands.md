# Arch (Manjaro Sway) linux basic comands after install

- sudo pacman -Syyuu

- sudo pacman -S git timeshift

- sudo pacman -S lib32-mesa vulkan-radeon lib32-vulkan-radeon vulkan-icd-loader lib32-vulkan-icd-loader

- sudo timedatectl set-local-rtc 1 --adjust-system-clock

- sudo pacman -S --needed git base-devel
- git clone https://aur.archlinux.org/yay.git
- cd yay
- makepkg -si

- sudo pacman -S --needed base-devel git
- git clone https://aur.archlinux.org/pikaur.git
- cd pikaur4
- makepkg -fsri

- pikaur -S nerd-fonts-noto-sans-regular-complete ttf-unifont ttf-symbola ttf-jetbrains-mono

- git clone https://aur.archlinux.org/snapd.git
- cd snapd
- makepkg -si
- sudo systemctl enable --now snapd.socket

- sudo snap install btop

- sudo pacman -S kitty fish thunar ranger neofetch neovim
- chsh -s /usr/bin/fish

- git clone https://aur.archlinux.org/visual-studio-code-bin.git
- cd visual-studio-code-bin/
- makepkg -si

- git clone https://aur.archlinux.org/google-chrome.git
- cd google-chrome/
- makepkg -si

- sudo pacman -S telegram-desktop discord flameshot vlc variety firefox-developer-edition unrar unzip transmission-qt copyq

- sudo pacman -S nodejs-lts-fermium npm yarn

- sudo npm install --global typescript gulp

- sudo pacman -R firefox

- sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
