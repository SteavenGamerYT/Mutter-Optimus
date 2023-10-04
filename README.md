# Mutter-Optimus
Fixes an issue that I had on Gnome for years!

## Installtion Command
```sh
sudo pacman -S --needed git base-devel
git clone https://github.com/SteavenGamerYT/Mutter-Optimus
cd Mutter-Optimus
makepkg -si --skipinteg --skipchecksums --skippgpcheck
```

## What does it do?
Applies:

https://gitlab.gnome.org/GNOME/mutter/-/merge_requests/3304

https://gitlab.gnome.org/GNOME/mutter/-/merge_requests/1441

 to Mutter 44.5

Fixes:

https://gitlab.gnome.org/GNOME/gnome-shell/-/issues/6221

https://bugs.launchpad.net/ubuntu/+source/mutter/+bug/1970291

https://gitlab.gnome.org/GNOME/mutter/-/issues/2247