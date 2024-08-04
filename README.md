# hypr.danna

<p align="center">
  <img src='https://i.postimg.cc/DyrwxYCV/image.png'>
</p>

## Información

### Welcome! These are my dotfiles <33
This is from the Danna repository. I am going to give you instructions and the necessary dependencies for my theme. ^^

### ‼️ Important !!
- Not works in Nvdia (well, i don't try it xd).
- The fonts will be installed in another steps.
- Change the name of your monitor un the hyprland configs.

### 🍧 Information
[Fonts here](https://mega.nz/file/GxFVSLLY#etuNc6QRrEl6wgl_ZatvomojDhkBTFPqlKS7ELk7KAM)

-  **OS** Arch Linux
-  **SH** zsh 5.9
-  **TM** kitty 0.35.2
-  **WM** Hyprland (Wayland)

## Steps for install

### Install necessary fonts and reboot.
```sh
sudo cp -r ~/Downloads/* /usr/share/fonts/*
```
Install your favorite desktop manager, I use emptty.
```sh
sudo pacman -S emptty
systemctl enable emptty.service
```

🔧 Script
```sh
git clone https://github.com/danxnya/hypr.danna.git && cd hypr.danna/
chmod +x setup.sh
./setp.sh
```
Now, only wait and ENJOY. ><


👤 Author
danxnya
