# Taiko-no-Tatsujin-The-Drum-Master-Patch

This patch allows for the game to go past the title screen for version 1.1.0.0 on Windows PC. 

Note: You may need to enable mods from the Xbox app to obtain permissions to overwrite game files. 

1. Download Taiko Patch.xdelta, This is a patch file containing the changed code from my decompiled version to the original. 
2. Get DeltaPatcher from https://github.com/marco-calautti/DeltaPatcher
3. Note your game's installation directiory, yours might be under `C:\Program Files\ModifiableWindowsApps\Taiko no Tatsujin\Taiko no Tatsujin_Data\Managed` and look for `Assembly-CSharp.dll`\
(My installation directory is different)\
![](https://github.com/Fluto/Taiko-no-Tatsujin-The-Drum-Master-Patch/blob/main/1.png)

5. Using Delta Patcher, select the original file as `Assembly-CSharp.dll` and the XDelta Patch from the one you downloaded in Step 1\
![](https://github.com/Fluto/Taiko-no-Tatsujin-The-Drum-Master-Patch/blob/main/2.png)

6. Apply Patch
7. ???
8. Profit? Play the game!


The dev team was trying to silently sign the player in when playing for the first time. However with GDK for Windows you need to prompt the player for the first time to sign in. Then silently sign in afterwards. 
What this patch does is force the titlescreen to ask the player to sign in. 
Can't post the code here due to IP issues. 
