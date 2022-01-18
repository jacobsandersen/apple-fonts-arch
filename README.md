# Apple Developer Fonts for Arch Linux
Retrieved from the DMG files [provided by Apple here](https://developer.apple.com/fonts/).


## Demo
<p align="center">
  <img alt="demo img" src="https://owo.whats-th.is/9k97X19.png">
</p>


## To Install
It's easy as pie.

1. Clone repo:

    `$ git clone https://github.com/simpleauthority/apple-fonts-arch.git`

2. `cd` to the one you want. For example, **SF Mono**: 

    `$ cd SF\ Mono`

3. Install the package:

    `$ makepkg -si`

4. **(optional)** Refresh your font cache:

    `$ fc-cache -r`


## To Uninstall
Also easy as pie. Pick one. Or all.

* `$ pacman -Rcns apple-fonts-sf-pro`
* `$ pacman -Rcns apple-fonts-sf-compact`
* `$ pacman -Rcns apple-fonts-sf-mono`
* `$ pacman -Rcns apple-fonts-sf-arabic`
* `$ pacman -Rcns apple-fonts-new-york`

Then, maybe refresh your font cache again **(optional, again)**: 

* `$ fc-cache -r`


## By the way...
I have **LITERALLY** no idea what the license on these fonts is. However, they're freely downloadable even without an apple developer account so I assume it's okay. But, that is why I am not putting these on the AUR. They will be here in this GH repo instead. You can manually install them via the PKGBUILDS.


## That's it, bye.
