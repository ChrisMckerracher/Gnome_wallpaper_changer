Gnome_wallpaper_changer
=======================

Changes the wallpaper for gnome-shell depending on the time of day

Installation:  
1) chmod +x random_wallpaper  
2) place the random_wallpaper script in a directory of your choosing  
3) configure crontab to run the script however often you want
4) create subfolders ~/Pictures/Wallpapers/(Rest,Night,Morning, and Sunset) and fill the folders time-specific wallpapers
  
Ex: My cron job looks like:  
*/15 * * * * '/home/chris/bin/random_wallpaper'  
