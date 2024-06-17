# Starwars theme for Grub/Grub2

## Preview

![Grub preview](preview.png)

## How to install

Open a terminal cd'd to the directory of the source code, and run the following commands:

`sudo chmod +x install.sh`

`sudo ./install.sh -s <screen-size>`

#### Screen size:

- 1920x1080 - 1080p
- 2560x1440 - 2k
- 3840x2160 - 4k
- 2560x1080 - ultrawide
- 3440x1440 - ultrawide2k

#### Examples:

If your monitor is of the resolution 2560x1440:

`sudo ./install.sh -s 2k`

To remove the theme:

`sudo ./install.sh -r`

To open the help menu:

`sudo ./install.sh -h`

## Notes

- Code isn't completely clean, contains some dependancies from the original source code, which was modified to accomodate the new theme files. Will be cleaned eventually.

- TUI Installation menu for simpler installation will be added later, alongside improvements in error handling.

## Credits

Based on [vinceliuice's grub2-themes](https://github.com/vinceliuice/grub2-themes).

