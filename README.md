Author: Ryan Zollinger (Dr. Puzzler#1894)

Made for James Lightfoot

This script changes the frame flipping state of an AC character prefab based on the current scene. This script is specifically made for the case of using a player prefab that is automatically placed in the scene from the AC settings manager.

How to use:

Step 1: Attach this script to your player prefab

Step 2: pick the default setting that you would like the player prefab to have. This is important, because rather than using the setting that is defined in the player script, the setting will be altered to whatever is selected in this script.

Step 3: pick the new setting that you want the player prefab to have in the defined scenes.

Note on step 2 and step 3: It is important that you pick only one setting in each category, no more, no less. The script will not function properly if you pick more than one, or if you don't pick any. If no option is chosen, then no change will be applied. If more then one option is chosen, then the first option that is chosen in the list will be applied.

Step 4: Choose the scenes you want to apply a change to. This must be by scene name, not scene number. This will make it so the change is made in the correct scene even if the order of scenes in build settings is altered.