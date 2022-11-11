# planner-old-theme

### Update:
The bug this repo was solving by the downgrade was fixed on to the newer version of the app (mostly arch based distros affected), rendering this repo not useful anymore, only as a reference to which once was an annoying issue caused by packaging stuff.

zip files to downgrade elementary-planner theme to version 5 due recent upgrade breakage.
Extract them and run:

- sudo pacman -U gtk-theme-elementary-5.4.2-1-any.pkg.tar.zst
- sudo pacman -U elementary-icon-theme-5.3.1-1-any.pkg.tar.zst

If you havent cleaned your cache this commands should work as well without the need of extracting the files:

- sudo pacman -U /var/cache/pacman/pkg/gtk-theme-elementary-5.4.2-1-any.pkg.tar.zst
- sudo pacman -U /var/cache/pacman/pkg/elementary-icon-theme-5.3.1-1-any.pkg.tar.zst
