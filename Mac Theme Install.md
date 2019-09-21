# How to install Mac Theme on Manjaro Linux

Reference Video: [Click here](https://www.youtube.com/watch?v=y-wEQddNVIE)

Install Theme & Icon by Terminal: [click here](https://manjaro-tutorial.blogspot.com/2018/09/how-to-make-manjaro-180-looks-like-mac.html)

```
https://github.com/B00merang-Project/iOS

move the extracted folders to /usr/share/themes.

sudo mv iOS-master /usr/share/themes

=> Go to Appearance > Style > iOS-master
```

```
https://github.com/keeferrourke/la-capitaine-icon-theme

You need to move this folder to /usr/share/icons

sudo mv la-capitaine-icon-theme-master /usr/share/icons

=> Go to Appearance > Icons > La Capitaine
=> check the icon and fix the problem
```

```
https://github.com/B00merang-Project/macOS

move the extracted folders to /usr/share/themes.

sudo mv macOS-master /usr/share/themes

=> Go to Window Manager > set macOS-master
```

```
1. Go to Add/Remove Software
2. Search "Docky"
3. AUR - Install 

** Fix the problem "unknown public key" => gpg --recv-key 8F0871F202119294 (Enter the key ID as appropriate)
Reference: https://bit.ly/2kwntgH
```

### Remove the shadow of the Docky - Horizontal Line Across Screen on Xfce
[Click here](https://nochkawtf.wordpress.com/2015/05/03/horizontal-line-across-screen-on-xfce/)
