# Archi Linux / Sway / my Setup

### Clone files in this repo to:
`/home/username/.config `

## Create file .gtkrc-2.0 in folder:
`/home/username/ `

> Add this text to file next

`gtk-theme-name="Breeze-Dark"`

`gtk-icon-theme-name="breeze-dark"`

### Install theme and utility (open terminal):
`sudo pacman -S breeze breeze-gtk breeze-icons mako wofi `

### Install fonts:
`sudo pacman -S noto-fonts noto-fonts-emoji`

> Clear fonts cache `fc-cache -rv`

> Reboot system `reboot`

> Send test alert `notify-send "🔔 Alert" "This is test 🎉"`

### Install USB utility:
`sudo pacman -S udisks2 udiskie`

### Install Git:
`sudo pacman -S git`

### Install AUR:

>`git clone https://aur.archlinux.org/yay.git`

>`cd yay`

>`makepkg -si`

### Install other packages:

#### Utilities:
- `bpytop`
- `htop`
- `neofetch`
- `udisksd`
- `duf`

## File Manager:
- `pcmanfm`
- `ranger`

## Text Editor:
- `mousepad`

## Images Editor:
- `mtpaint`

## Screen Shot:
- `grim`
- `slurp`

## Code Editor:
- `visual-studio-code-bin`

## Browser:
- `firefox`
- `lynx`
- `qutebrowser`

## Remote Desktop:
- `remmina`
- `freerdp`

## FTP:
- `filezilla`

## Zip Archiver:
- `xarchiver`
- `p7zip`
  
## Media Player:
- `vlc`
- `mpv`

## Live Wallpaper:
- `mpvpaper`

## Security:
- `keepassxc`

## Office:
- `libreoffice-still`

## Command for fust install packages:

`sudo pacman -S bpytop htop neofetch udisksd duf pcmanfm ranger mousepad firefox lynx qutebrowser remmina freerdp filezilla xarchiver p7zip vlc mpv keepassxc libreoffice-still grim slurp mtpaint`

`yay -S visual-studio-code-bin goole-chrome mpvpaper`

