
# grub-bgrt theme

A theme for GRUB2 which uses your system's UEFI logo (aka BGRT).

## Font

To change the font in the theme, try something like:

	grub-mkfont -o dejavu_12.pf2 -a -s 12 /usr/share/fonts/truetype/dejavu/DejaVuSans.ttf

(-a adds antialiasing, -s 12 sets the size to 12). Don't forget to update the `theme.txt.in` as well.

## License

All the files in this project are distributed under the [GNU General Public License](./LICENSE).

## Author

Paul Saunders

## Forked from

https://github.com/fghibellini/arch-silence
