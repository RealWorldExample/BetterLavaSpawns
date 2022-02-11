# BetterLavaSpawns

Version 1.0.0 only updates the gamemode _floor_is_lava to exclude spawns that are on buildings and are potentially oob (out of bounds) this makes a huge difference playing on complex, crashsite, and drydock.

Version 1.1 Revised the spawns in live fire maps, and brought the fog back for Stacks and Deck. The fog on these two maps is still invisible.

In the future needs to add damage to auto-titan

Next needs to exclude spawns outside of walls but not technically oob.

Then spawns need to consider enemy team proximity, or all of this lava spawning needs to be included in the spawn.nut as an if statement or something.

# How to use

Add this mod to the mods folder of you dedicated server

Add "riff_floorislava 1" to your +setplaylistvaroverrides located in your ns_startup_args_dedi.txt
                            v------Somthing like this------v
+setplaylist private_match +ns_private_match_only_host_can_change_settings 2 +setplaylistvaroverrides "run_epilogue 0 classic_mp 0 timelimit 12 riff_floorislava 1"

