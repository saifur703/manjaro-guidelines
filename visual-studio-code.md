# Installing Visual Studio Code (VSCode) on Manjaro linux

Browse this link: http://umaranis.com/2018/07/05/installing-visual-studio-code-vscode-on-manjaro-linux/

## Install from "Add/Remove Software"

After enabling "AUR" repository in "Add/Remove Software" app, search for "visual-studio-code-bin". There will be 2 software in the search list. Right-click on the 1st result "visual-studio-code-bin" and click "Install".

## Install from AUR

1. Acquire build files from Arch Linux user repository.
```
curl -L -O https://aur.archlinux.org/cgit/aur.git/snapshot/visual-studio-code-bin.tar.gz
```
2. Extract the downloaded package
```
tar -xvf visual-studio-code-bin.tar.gz
```
3. Change directory to the extracted package
```
cd visual-studio-code-bin
```
4. Build and install the package
```
makepkg -si
```

# Configure VSCode
```
1. File > Preferences > Font-size: 18 pixel
2. Extention
    * Code Runner
         - File > Preferences > Settings > Clear Previous Output
         - File > Preferences > Settings > Save file before run
    * PHP IntelliSense
    * WordPress
```
