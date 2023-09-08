# Pushup Power
Base your Skyrim character's stats on how many pushups you can do in a row without stopping.

## Simpler Method
1. Open up the console in Skyrim by pressing the ` key
1. If you're doing a melee build and can do 15 pushups in a row, type in `player.setav MeleeDamage 15` and press enter. That will set your base melee damage (which is usually zero) to 15, and your weapon adds onto that.
1. If you're doing a bow and arrow build, type in `player.setav Marksman 15`

## Harder Method
1. Download pushups.txt from the Skyrim folder.
1. Find and replace all of the `FIND_AND_REPLACE_ME` with the number of pushups you can do.
1. Put the file into Skyrim's Data folder, `...\steamapps\common\Skyrim Special Edition\Data\pushups.txt`
1. Open Skyrim
1. Open the console with `
1. Type the command `bat pushups` and each line of the txt file will run, updating all of those stats.