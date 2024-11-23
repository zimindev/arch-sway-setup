# Archi Linux / Sway / my Setup

## Clone files in this repo to:
`/home/username/.config `

## Create file .gtkrc-2.0 in folder:
`/home/username/ `

> Add this text to file next

`gtk-theme-name="Breeze-Dark"`

`gtk-icon-theme-name="breeze-dark"`

## Install first theme and utility (open terminal):
`sudo pacman -S breeze breeze-gtk breeze-icons mako wofi `

## Install fonts:
`sudo pacman -S noto-fonts noto-fonts-emoji`

> Clear fonts cache `fc-cache -rv`

> Reboot system command `reboot`

> Send test alert `notify-send "🔔 Alert" "This is test 🎉"`

## Install USB utility:
`sudo pacman -S udisks2 udiskie`
