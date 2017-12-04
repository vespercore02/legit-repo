RO EXP Viewer is a small tool to display the current experience a character has in the game Ragnarok online
and perform calculations with it to show the user interesting estimates when leveling.

Unlike (most of) other Ragnarok Online Experience viewers this tool does not require manual updating to find the values in memory.
Unless the game receives drastical changes it should just work.
It has been tested and found working on the international and european renewal version of Ragnarok Online.
But it should also work for other servers.
iRo classic and sakray server configuration are in the AdditionalConfigs folder. Just copy the Client.xml file you need in the main folder of this tool.
If you want to go back and use it on the regular renewal servers after that just delete or rename the config.xml.

This program needs to be "Run as Administrator" to be able to read from the computers memory.
It also requires at least .NET Framework 4 to be installed on the system.


The interface shows your current characters name and map from wich the exp is read.
Changing map or character resets the timer for the estimates, so it starts as soon as the player enters his leveling map.
It can also be manually reset with the "R" button in the top right corner.

If you are running multiple clients at the same time, you can use the "C" button the switch between active running clients until you see the character name you want to track your progress for.

The Checkbox enables and disables "Always on Top" functionality.
If you are playing the game in windowed mode you can position the Exp Viewer over your running client and almost see and use it as a regular ingame window.
The program saves its window position when closed. If you somehow managed to move it to an unreachable position, congratulations!
In this case you can however reset the window location right clicking the tray icon and selecting "Reset Position" (by default at the bottom right of your windows taskbar).
Using this tray icon you can also switch between an expanded view and the standard small view. The expanded view also shows %-values next to gained exp and exp/hr.
Switching the view however resets the current session.
Another option using the tray icon is to disable or enable the automatic reset on map changes.
The window can be collapsed and fold apart like a ingame window with the button left to the close button or using the hotkey: Ctrl + W


Base experience values are shown on the top, Job expereince values below base.
Gain - shows the last gained exp (in 100ms), if you kill multiple monsters in one hit it will be summed up since this tool can only detect changes in the experience a character currently has on his current level.
Total Gain - is an option you can switch to, by either klicking on the "Gain" Text, or using the Tray Icon menu.
TNL(till next level) - shows the kills needed with the current gain to reach the next level up.
Exp/Hr - shows your current experience gain in one hour. The longer you stay on a map, the more precise it gets.

Below those there are
current exp / exp required for level up shown on the left and the percent value with 2 digits after decimal on the right.

At the bottom of the window
on the left: Time the current session is running (only in expanded view)
in the middle: Estimated leveling time required with current speed (exp/hr) to reach your next base level up.
on the right: the same for your job level.


This program only reads single values from memory.
It does not read, alter or send network packages, it does not alter memory and it does not automate player activities.
Values read: base level, base exp, base exp required for level up, job level, job exp, job exp required for level up, character name, current map 

All of those values are also user accessible by normal means.
current exp: character select screen (or calculated from %)
base & job level: basic information window
character name: obviously given by the user, on character select screen and basic information window ingame.
current map: /where ingame command