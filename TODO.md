# Developer To-do List

#### Mince:

* Invulnerability conds cause arms to disappear with bonemerged robot/custom player model
* Need to test wave complete / wave fail / mission completion etc for attributes, make sure things are getting cleaned up
* Remove arms and bonemerged models / reset model of players when their attributes arent present
* Try to see if we can detect thirdperson to redisplay the bonemerged custom model instead of simply on taunt
* Once varargs is done, rename HandModelOverride to ModelOverride which can either change HAND_MODEL or PLAYER_MODEL, maybe PROP_MODEL too?
* After this redo the playersarerobots incompatibility with the new ModelOverride since it also might include player models
* ScriptLoadTable and ScriptUnloadTable?
* (ItemAttributes / PlayerAttributes) fix attributes carrying over on classes for some reason
* Finish LoadoutControl once we have our own giveweapon funcs
* Change format of playerattributes and itemattributes to be consistent with loadoutcontrol
* Modify PlayersAreRobots or make a new attr for changing robot vo to human (use this in ReverseMVM)
* Reimplement the Error system with try catch and throw
* (HolidayPunchFix) Check if we need to set m_hOwnerEnity since we already use SetOwner
* (ReverseMVM) Fix laser on sniper for human anims
* (ReverseMVM) See if we can forcibly jump to the next wave somehow when firing a game_round_win

<p></p>

* Fix AnimatedViewControlAll camera movement
* Implement the rest of the functions for tutorialtools.nut
* Unsure of how the global moneyfix will interact with the ReverseMVM money collection code, need to test
* Make a human / zombie voices override for reversemvm and add support for giants (for robos use the sounds, for others deepen the voice pitch)
* Add the robo idle sound?
* Find out a way to remove robo footsteps when we're on blue and not a robot, maybe a think sending StopSound?
