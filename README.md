# unnamed-doom-horror-mod
Doom mod based on an older mod "Scary Movie". Mod focuses on multiplayer, specifically Last Man Standing Game Mode on Zandronum.

 - All players begin with a flash light that works with dynamic lights. 
 - When the killer is selected, they will recieve a message and weapon upon said selection and try to kill the other players before the timer runs out. 
 - This timer scales with the amount of players in the current match. 
 - If the killer is unsuccesful to defeat all the other players. killer is killed and another player gets to be the killer.

   This project uses the `zandornum` sourceport which can be found here: https://zandronum.com/download
   Given that it is a doom mod, you are to provide yourself the means to obtain the `DOOM.wad` file to play the base game and the mod through `zandronum`.

   The mod stictly works in the Last Man Standing game mode within `Zandronum` which makes it a multiplayer only mod. To run the mod, download the project as a `zip` file and instead of extracting the contents of the file, rename the file extension to `pk3` which is a compatible extension for `Zandronum`.
**The script that allows the mod to operate only initializes when there's another player or bot in the game.**

<h1>Known Issue</h1>

**If the map that is played on has less player start points than the number of active players, the script that assigns the KillerID breaks given that spawn kills alter the active players dead flag.**

![Screenshot_Doom_20220831_143632](https://github.com/Kobkev/unnamed-doom-horror-mod/assets/48692724/718dc162-cad7-4105-8055-5de597877e1d)
