# Titanfall 2 Killsounds Plus
Custom Killsounds for Titanfall 2

This is a guide and a base to modding your killsound for the Titanfall 2 Northstar client.

Download Oof_killsounds.zip if you only want one killsound, and KillsoundsPlus.zip if you want multiple, setup should be the same for both files

For the setup:
1) Copy and paste the contents of the autoexec.cfg file given into your autoexec.cfg file in your Titanfall2\r2\cfg folder. 
   If it's not there, move the provided one in that spot instead.

2) Go to Titanfall2\ns_startup_args.txt and add in: +exec autoexec.cfg

3) Extract and drag the rest of the files into your Titanfall 2 folder (NOT Titanfall 2\R2 Northstar\mods folder) 

For Customisations:
If you want to change your killsound to something else other than the provided minecraft oof sound. You need to change the killsound.bik provided to your own file.
killsound.bik should be located in Titanfall2\r2\media

If you want to change it, remember that your file has to be in the .bik format. It won't play if it is not a video.


For Killsounds plus:
1) The provided file only has 4 Bruh#2 sound effects in it so you have to customise it yourself. my suggestion is to use mp4 to .bik using RAD tools. I have no idea how other converters would work out.
2) Go to your Titanfall2\r2\media folder and change the killsound1,killsound2, killsound3,and killsound4 to the ones you want

-If your custom sounds don't work, try using the default files. 

-The randomiser might not work if you are not using the wasd keyboard layout as it is bound to the wasd keys and you might need to change the last 4 lines of the autoexec.cfg file from "bind w +w" to "bind [your key here] +w" change accordingly for the 4 lines. You dont need to change the +w part, if you do change it, you need to change all the aliases as well.
