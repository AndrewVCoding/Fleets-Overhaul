# Fleets-Overhaul
A mod to re-balance fleet size and combat in Stellaris

############
#Disclaimer#
############
	This document is more me throwing shit at a wall and hoping some of it sticks and ends up being improving the combat in Stellaris. While We've tried a few other mods that change ship behaviors, add more classes, and aim to improve battles, none of them quite have what we want. This is to outline the main goals and ideas for this mod, whether they can all be implemented or not.

#########################
#What is this mod about?#
#########################
	One thing we want to emphasize is the importance of each individual ship in terms of cost and function.	We also want to encourage keeping multiple fleets, each with different ship makeup and roles in the broader game.
		
	Limiting naval capacity while also increasing the cost/maintenace/naval size of capital ships makes them more of an investment. This also means you could only have ~40 of them, max, even if you forewent any other ships. But this would leave them vulnerable without escorts. Also, your ability to bring fire power against invading fleets or other military targets would be drastically reduced. I'm also hoping that this multiplies the effect of loadout and choice of role for ships when engaging, so that fleet design has more weight to it.
	
	As far as weapons go, I think all weapon types should be available at the start, but whichever you chose as your starting type would be level 2. Maybe you could also have a boost to research on that weapon type, or the higher level you have the more likely the next level research is to appear. This allows for some more diversity in ship design and function from the beginning, and makes more sense as anyone who has discovered lasers has likely also discovered how to explode chunks of metal out of a tube.

#######################
#Ships and their roles#
#######################
Corvettes
	Based on modern Littoral Combat Ships. Small, versatile ships with offensive and defensive capabilities
		Sometimes even the ability to carry a couple of helicopters
			Might give a module with one hanger bay to represent that
	Fairly standard, not much change other than increased maintenance cost
	should be faster and more agile, but lower health
	These would make up the bulk of your navy, at around 40-50% of your ships

Frigates
	Primarily play a defensive role for other ships
	Meant to provide escort, boasting point defense and small weapons slots
	These have been primarily phased out of modern military, as other ship classes cover their roles, so I may not use them

Destroyers
	Can also fill the role of escort, but strong against large targets
	Outfit torpedoes and missiles?
	fast and maneuverable, but less so than corvettes

Cruisers
	These basically smaller, faster battleships, better suited to scouting missions and confronnting enemy fleets
	They are well armoured and have strong defenses in point defense
	They can bring a few large weapons for large targets while also sporting medium weapons to take out large ships
	If going up against corvettes, they may need escorts with small weapons however
	
Battleships
	These beasts are big and expensive, boasting several large weapons, and an array of medium weapons and torpedo tubes
	They excel at countering enemy fleets that were sent out to attack systems
	The maintenance costs and naval capacity of these makes it impractical to have more than a few, and losing one is a big deal
	
Carriers
	These are the mobile cities that modern aircraft carriers are. They're not very maneuverable, but can still get up to speed.
	They have the hangar capacity to let loose small swarms of strike craft and have a high amount of hull points
	Utility slots are important to provide sheilds and armor.
	Carriers are a large investment, and losing one can be devestating, so be careful about how you deploy them
	
############
#Navy Costs#
############
Max Naval Capacity = 1500
	Corvettes	= 4
	Frigates	= 5
	Destroyers	= 10
	Cruisers	= 20
	Battleships	= 30
	Carriers	= 35
	Titans		= 100 (These are truly massive ships requiring a lot of upkeep, and should be rare and valuable even for fallen empires. Also very hard to kill)

############################
#Example Navy Fleets makeup#
############################
	This would be a decent sized navy that would be able to cover the territory of a small empire quite well, but a large empire might have many more patrol fleets, some more attack fleets during war, and possibly a second main fleet. So perhaps set max naval capacity to around 1500...
	
Example fleets: 678
	1x Main: 				238
		2 Carriers		= 70
		3 Battleships	= 90
		6 Frigates		= 30
		12 Corvettes	= 48
	1x Attack:				220
		2 Battleships	= 60
		4 Cruisers		= 80
		6 Destroyers	= 60
		4 Frigates		= 20
	2x Patrol:				110
		1 Battleship	= 30
		2 Destroyers	= 20
		4 Frigates 		= 20
		10 Corvettes	= 40

Naval capacity that big would also allow you to create a fleet that was:
	42 Carriers, or 50 Battleships, so fleets that are bunches of carriers, battleships, and cruisers are possible, but should be incredibly expensive and specialized. Again, I'm looking to keep the total number of ships fairly small and make it less viable to spam either only large ships or just naked corvettes. Maybe max naval capacity would be better somewhere around 1000, depending on how close most empires can actually get to the max in the span of a normal game.

##############
#Fleet Growth#
##############
	At the beginning of the game, one might expect an empire to be just starting on constructing space fleets, with perhaps only a couple of new, experimental ships their navy has constructed as a show of power. Having not discovered any other empires in space, they probably aren't too focused on putting weapons up their just yet. So there won't be many resources to bolster your fleet size. Perhaps those couple of corvettes are what helped unify your race under a single government? Either way, small fleet to begin with.
	As you colonize new systems and develop the technology to build larger space structures and upgrade your space ports, your fleet size can grow quite a bit. Since space ports are where ships can dock and where crew are assigned to their respective ships, they provide a fairly decent bonus to naval capacity, but the real benefit comes from populations since, after all, somebody's got to steer those things. Also, if your empire has a tradition of keeping a large standing military, than a perk of 200 extra naval capacity is quite the bonus.
	
spaceport level bonus to naval capacity:
	1 = 12
	2 = 24
	3 = 36
	4 = 48
	5 = 70
	
	So with 5 planets, you could get 350 naval capacity from just space ports, and then populations might provide another 400-500 possibly? IDK, this is definitely something I'll need to experiment with and figure out what feels like good progression. On one hand, of course a larger empire should have a larger naval capacity, but I also want vertical progression to be viable and for empire size to have less overall impact on military success. A small empire that has better fleet management and composition should still be able to compete with the big boys in the playground.
	
#########
#Weapons#
#########
	Having all weapons unlocked from the beginning, but specializing in a particular direction, opens up the possibiity for more varied fleets. I'm not really sure how possible this is with simple modding, but I'm hopeful it won't be too difficult. Probably won't be my first priority, but definitely on the list of todos. I do want to rebalance weapon costs and power, especially the trade off from small-medium-large weapons and between the different levels and types.

	Projectile weapons should use some energy, but mostly minerals,
	Missles should use fewer energy but more minerals,
	Lasers should use a lot of energy but very few minerals

	After all, throwing chunks of metal at enemy ships means you had better be making a bunch of ammo. Missiles are going to be bigger and use more material, but aren't being gimballed on the ship, taking up power. Lasers really aren't using any material, unless some is being used as a fuel source, but sure suck up a lot of juice. These balances can be applied to monthly maintenance of ship modules.

As for damage:
	Projectiles can penetrate armor, doing damage to the hull, but have trouble getting through shields
	Lasers quickly overload shields with energy but a lot of their energy is diffused by armor
	Missile explosions can damage armour of multiple ships, and expose the hull, but are vulnerable to point defense systems
		They also have the ability to acquire new targets if their current target is destroyed, not sure yet what value to set 			that to...

##################
#Fleet Formations#
##################
	Fleets should stay relatively close together, able to protect each other. Strike craft from carriers cross the void between fleets, dodging flak and beams from both friend and foe as they close the distance on their target. A pilot turns off his targeting computer in a moment of stupidity, as his bombs miss their mark. As he comes back around for another run, a stray shell from his own fleet punches through the cockpit and the vacuum of space yanks his body out into the abyss.

	What can I say, I really liked BSG space combat. After playing some more recent campaigns of Stellaris, where fleets are stacking up around 100 ships, I'm starting to notice how suicidal corvettes are in these big fleets. I'll go into battle with 30-50 corvettes and maybe 30 destroyers, and they'll all die in just one battle. But I don't really lose much fleet power because only a couple of the larger ships bite the dust. In keeping with the theme of "Every ship is an investment", I want to ensure that corvettes and cruisers aren't just rushing headlong into the enemy fleet, but that they stay in some sort of battle formation. And then strike craft can be the kamakazis.

	So, to hopefully balance this, ships will be set to stay grouped up and keep their distance from the enemy fleet. In addition, fleet order will be moved so
that the escort ships stay near the middle of the fleet, tanky ships near the front, and the really valuable capital ships can take up the rear.

	(Rear)----------------------------------------------------------------------(Front Line)
	(Carriers)  (Titans)  (Battleships)  (Frigates)    (Destroyers)   (Cruisers) (Corvettes)
	
#############
#Space Ports#
#############
	As they are right now, space ports become useless for defense past a certain point in the game. Fleets just become too powerful for a space port to not pop at the mere sight of one entering the system. Then you have to spend the resources to build it back up, which by this point in the game is more annoying than it is detrimental to your empire's defences. Space ports are the bases for your WHOLE NAVY! They should be able to withstand an assault from an enemy fleet for some time when high level. But also should cost a lot to upgrade to high levels. That way, when one gets destroyed it's actually somewhat of a setback instead of the mild inconveniance it is now. And that gives you more of a reason to keep a competent fleet nearby to jump in to defend it. But they need to be buffed so that they survive long enough for a nearby fleet to get there.
	Now obviously the low level ones can't be too strong, otherwise trying to invade a planet before getting cruisers would be nigh impossible, so their defensive capabilities should scale a lot with upgraded levels, and with added defenses.
