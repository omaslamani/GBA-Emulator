# Welcome to GBA Emulator

GBA Emulator is a free, online GBA emulator! There are over 50+ games to play! Simply click the link provided below and click on the game you would like to play. From that point, you should be good to go!

# Click Here to Play!

https://theclashman2.github.io/GBA-Emulator/

# Saves and Game Progress

You can come back and play whenever you want! Our save system works via browser cache. As long as you use the same browser (and don't clear your cache), all of your data will be stored! Make sure you still save your progress in-game to come back and play.

You can always download your save file by downloading your cache data and loading the save file into another emulator! Unfortuantely, we have yet to add support for loading custom save files. 

# Controls for games

![image](https://user-images.githubusercontent.com/58522488/218331500-d54e0f61-d5c4-419c-ac4b-da12e7579069.png)

Looking at the GBA, here are the button layouts for the controls:

- Start: Enter
- Select: Shift
- A: X
- B: Z
- L: 1
- R: 2
- D-Pad: Arrow keys.

Unfortuantely, we do not support any button or key mapping, neither do we have controller support (unless done via a third party application binding your controller keys to the following PC keys. 

# Adding More Games

Here is a list of steps to add any GameBoy Advance Game to the list. Do these sets of steps AFTER cloning the repository for yourself.

1. Upload a VALID .gba file inside of the **Binaries** directory
2. Go to the **index.html** file
3. Use the following format to paste the following in the list **IN ALPHABETICAL ORDER**. Make sure this line is encapsulated in a li and a HTML element
- <href="./launcher.html#**FILENAME**">**GAME NAME HERE**

