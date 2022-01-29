# Taiko-no-Tatsujin-The-Drum-Master-Patch

This patch allows for the game to go past the title screen for version 1.1.0.0 on Windows PC.

0. **You may need to** ![enable mods](https://support.xbox.com/en-AU/help/games-apps/game-setup-and-play/enable-pc-game-mods) **from the Xbox app to obtain permissions to overwrite game files.**

1. Download ![BepInEx](https://github.com/BepInEx/BepInEx/releases) `BepInEx_x64_XXXXX.zip`, as of writing the latest version is 5.4.18. This is a mod to patch Unity Games
2. Find your game's installation directiory, yours might be under `C:\Program Files\ModifiableWindowsApps\Taiko no Tatsujin\` 
3. Paste all of the files from the .zip from step 1 into this folder
(It will look something like this, my directory is different because I installed it to a different folder)\
![](https://github.com/Fluto/Taiko-no-Tatsujin-The-Drum-Master-Patch/blob/main/3.png)
4. ![Download my patch](https://github.com/Fluto/TaikoMods/releases/tag/v0.0.1), this contains the code to fix the bug
5. Run Taiko no Tatusjin The Drum Master once, then close it
6. Look in your game's folder again, new files will have been generated under `.\BepInEx\plugins`
7. Paste the .DLL from step 4 into this folder\
![](https://github.com/Fluto/Taiko-no-Tatsujin-The-Drum-Master-Patch/blob/main/4.png)
8. ???
8. Profit? Play the game!

The dev team was trying to silently sign the player in when playing for the first time. However with GDK for Windows you need to prompt the player for the first time to sign in. Then silently sign in afterwards. 
What this patch does is force the titlescreen to ask the player to sign in. 

---

I updated the patch method to not be a destructive change. Hopefully what this means is that when the update is released to fix this issue, you wont need to do any extra work to remove this mod, it should hopefully just not apply the patch.

<details><summary>**Looking for the older patch instructions? Well you can find them here, just be aware that you may need to reinstall your game when the update comes out!**</summary>
<p>
When the next update comes out, this mod will no longer work, additionally you may need to **Verify and Repair** the game to make sure your files are as the developers expect it.

0. **You may need to** ![enable mods](https://support.xbox.com/en-AU/help/games-apps/game-setup-and-play/enable-pc-game-mods) **from the Xbox app to obtain permissions to overwrite game files.**

1. Download Taiko Patch.xdelta, This is a patch file containing the changed code from my decompiled version to the original. 
2. Get DeltaPatcher from https://github.com/marco-calautti/DeltaPatcher/releases/ (deltapatcher_v2.0.1_win32_bin.zip)
3. Note your game's installation directiory, yours might be under `C:\Program Files\ModifiableWindowsApps\Taiko no Tatsujin\Taiko no Tatsujin_Data\Managed` and look for `Assembly-CSharp.dll`\
(My installation directory is different)\
![](https://github.com/Fluto/Taiko-no-Tatsujin-The-Drum-Master-Patch/blob/main/1.png)

5. Using Delta Patcher (may need to run as admin), select the original file as `Assembly-CSharp.dll` and the XDelta Patch from the one you downloaded in Step 1\
![](https://github.com/Fluto/Taiko-no-Tatsujin-The-Drum-Master-Patch/blob/main/2.png)

6. Apply Patch
7. ???
8. Profit? Play the game!

</p>
</details>
