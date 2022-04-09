# Fatal-Frame-Maiden-of-Black-Water-Photos-Viewer
Tool designed to decode and load all the saved photographs made with the camera obscura in the Fatal Frame Maiden of Black Water game

Did you know that you can only save up to 160 photographs per save in your game? Although you can firstly make a backup of your photos and then delete all of them in game, and still be able to load them with this tool later on.

After finding the save files location and seeing all the "PHOTODATA..." files, I tried for several minutes to decode them without much success, so I created this dedicated tool to "scan" different widhts for the same image, until I managed to find the real width, and having the file size and pixel format (32 bits ARGB), it returned the height also, so now basically this tool loads all the photos with the default discovered settings, but it also supports any setting, effectively allowing it to be used to decode any image without header, as long as their bytes aren't compressed (they must be like BMP format for this to work), so feel free to use it as you want, since it can literally convert any file type to a valid image, although don't expect to see anything after the conversion when using it for non image files.

Special thanks to Joeynator3000, since your comments inspired me to research even further into the game formats, resulting among other things in this new tool.
