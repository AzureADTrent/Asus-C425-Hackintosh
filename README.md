This is my personal attempt to get Monteray running on my Asus Chromebook C425. This was followed from https://github.com/meghan06/ChromebookOSX

Make sure to have https://mrchromebox.tech/ setup. Remove the battery BEFORE turning off WP if you don't have the SuzyQ cable. Make sure to push up the silver connector before pulling up the battery cable from the motherboard.

Lastly, make sure to add the moteray recovery using the opencore guide and format your USB. https://dortania.github.io/OpenCore-Install-Guide/installer-guide/

Currently not working:
/*:
-Keyboard backlight. --Followed the article from meghan06 but it failed to load.
-Audio --Unsupported codec at time of writing.
-Mic --Same as above.
*/
Issues:
/*:
-Wireless is not the fastest.
*/

This is a personal project and I will likely continue to work on this in my free time to get backlight working along with additional files to make audio/mic work in the future.
