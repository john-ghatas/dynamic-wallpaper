# Usage
Clone the folder in an accessible location (/home/$USER), and point to the .xml in each folder in Gnome Tweaks

## Recommended method
A script is supplied in which the background is automatically copied to the path defined in the XML which is `/usr/share/backgrounds/gnome/`. This method requires no changing of the XML file

Enter the following command in the terminal, this script uses sudo **please review it first before running it**:

```
./copy_bigsur.sh
``` 

Each set of wallpapers is seperated in their own folder, with a script supplied for each set.

After copying the files open gnome tweaks and point your background and/or lockscreen background to `/usr/share/backgrounds/gnome/BigSur/bigsur.xml` in Gnome Tweaks.

## Important 
Edit the paths in the XML to point to the correct location of the wallpapers when using different paths than used in the XML file
