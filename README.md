# planner-old-theme
zip files to downgrade elementary-planner theme to version 5 due recent upgrade breakage.
Extract them and run:

- sudo pacman -U gtk-theme-elementary-5.4.2-1-any.pkg.tar.zst
- sudo pacman -U elementary-icon-theme-5.3.1-1-any.pkg.tar.zst

If you havent cleaned your cache this commands should work as well without the need of extracting the files:

- sudo pacman -U /var/cache/pacman/pkg/gtk-theme-elementary-5.4.2-1-any.pkg.tar.zst
- sudo pacman -U /var/cache/pacman/pkg/elementary-icon-theme-5.3.1-1-any.pkg.tar.zst
