# Taiko-no-Tatsujin-The-Drum-Master-Patch

1. Download Taiko Patch.xdelta, This is a patch file containing the changed code from my decompiled version to the original. 
2. Get DeltaPatcher from https://github.com/marco-calautti/DeltaPatcher
3. Note your game's installation directiory `D:\XboxGames\T Tablet\Content\Taiko no Tatsujin_Data\Managed` and look for `Assembly-CSharp.dll`
4. Using Delta Patcher, select the original file as `Assembly-CSharp.dll` and the XDelta Patch from the one you downloaded in Step 1
5. Apply Patch
6. ???
7. Profit? Play the game!


What the dev team was try to silently sign the player in when playing for the first time. However with GDK for Windows you need to prompt the player for the first time to sign in. Then silently sign in afterwards. 
What this patch does is force the titlescreen to ask the player to sign in. Can't post the code here due to IP issues. 
