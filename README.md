## Amazones civilisation for 0 A.D.

### Overview
This is a mod for the free, open source RTS game [0 A.D.](http://www.play0ad.com) that adds an Amazone civilisation of female warriors. The ancient Greek had many stories relating to these fearsome women-only tribes of warriors (see for example the WikiPedia page on [Amazons](http://en.wikipedia.org/wiki/Amazons)), although it may not be entirely based on fact. The most reasonable explanation involves nomadic Scythian tribes comprised of mostly women, due to their men being out to war (or killed).

I wanted to try my hand at modding 0 A.D. and the Amazons were a fun starting point. This mod tries to use as much models, textures, animations and such from the core 0 A.D. game, so visually the civilisation is not very distinct (or coherent in building styles). Also, just a small number of structures and units are available, making it very hard to win a game because many defensive and offensive options are simply not available. Therefore I did not spent much time balancing units. But as far as a mini civ goes, it works fairly well.

### Play tips
* Most common technologies are available at the civil centre and the stables, to compensate for the lack of a farmstead and storehouse.
* Civil centres can be built closer together than with other civs to improve use of these as a drop point for resources.
* The Amazones lack any siege units, walls, and fortresses, nor is there a wide variety of champion units. This means to be successful you'll have to strike before your opponents reach the City phase.
* Creating female units from houses is a default capability (archers only), no technology needs researching first. Given that all female units are fighting units, this gives a tremendous capacity to create lots of units very fast.
* The technology that gives 10% health increase for female units can put them ahead of most competitors.


### Usage
Download this mod as a [zip file](https://github.com/dvangennip/amazones-0AD/archive/master.zip). Unzip it in the mods folder of 0 A.D., so it sits next to the `public` mod (you may want to rename it to `amazones` instead of `amazones-0AD-master`). Alternatively, you could use git directly to get the mod on your computer. Then run the game and enable the mod via the Mod Selection window, or run the game with an additional command line parameter (`-mod=amazones`) to indicate you want to use an extra mod as follows:

````sh
$ ./pyrogenesis -mod=amazones
````

For Windows:

````
your-0ad-folder> pyrogenesis.exe -mod=amazones
````

### Notes
* Requires an as-of-yet unimplemented [patch for 0 A.D.](http://trac.wildfiregames.com/ticket/1919) to enable packing and unpacking unit entities into structure entities for the mobile civ center to work as intended.
* Since many of the textures, animations and such use the default 0 A.D. ones, any changes made to those could impair the functionality of this mod.

### License
This work uses and references data from 0 A.D. and is published under a similer license: [Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)](http://creativecommons.org/licenses/by-sa/3.0/deed.en). This means you are free to share and remix the work, also for commercial purposes.
