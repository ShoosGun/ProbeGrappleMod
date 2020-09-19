# ProbeGrapleMod (first version)
Mod for the Alpha Outer Wilds version 1.2 that adds a graple rope to the game

### How do I install it?

1. Download the repo. and open the directory `Mod Instaling Kit`

2. Place all the files from that directory in `OuterWilds_Alpha_1_2_Data\Managed`

3. ####  IMPORTANT  Make a backup of the file `Assembly-CSharp.dll` and store somewhere else (it's good to rename it to something like "Assembly-CSharp-original.dll"), because the mod (for now) cannot remove it self from that dll 

4. Run the executable `GrappleModInstaller` **only once** , if no error occure it means that the mod has been succesfully installed, it will create a new file called `Assembly-CSharp-ModLoaded.dll`

5. Remember that I asked to backup `Assembly-CSharp.dll`? Now you have to delete it and rename the file `Assembly-CSharp-ModLoaded.dll` to `Assembly-CSharp.dll`

6. Run the game! 

### How do I uninstall it?

Simple, you just need to delete the modded `Assembly-CSharp.dll` (and,if you wish, all the other files that you placed from `Mod Instaling Kit` ), replace it with the backup you made when installing it and raname the file back to `Assembly-CSharp.dll`

### What it does?

It gives the player a new equipment to use: a *grappling rope*, it acts like a long rubber band and can have its size increased and decreased

### How do I use it?

Here is what each button does:

  **G** - Places the rope anchor at any aiming surface (you can be at max. 1.5 m away from it) | Retreives the anchor
  
  **T** - Makes the rope longer, at each half a second that the button is held, it has an increase of  75 cm
  
  **Y** - Same as the `T` button, but it decreases the rope size
  
