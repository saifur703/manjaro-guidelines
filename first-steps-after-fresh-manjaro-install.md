# First Steps After Fresh Manjaro Install

### Switch to Fastest Mirror
```
sudo pacman-mirrors --fasttrack
```

### Update Manjaro
```
sudo pacman -Syyu
```

### Install AUR package manager
```
sudo pacman -S yaourt
```

#### OR, To install yaourt , open the terminal and run
```
git clone https://aur.archlinux.org/package-query.git
cd package-query
makepkg -si
cd ..
git clone https://aur.archlinux.org/yaourt.git
cd yaourt
makepkg -si
cd ..
```

### Enabling AUR in Manjaro

(Enable AUR)!https://www.fosslinux.com/4278/what-is-aur-and-how-to-enable-it-in-manjaro.htm

