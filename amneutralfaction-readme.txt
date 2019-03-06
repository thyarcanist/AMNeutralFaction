Added Factions:
	ArchMagusFaction 
	ArchMagusSniffFaction #for the disguise spell)
	ArmorArchMagusFaction #for when armor is equipped)
Added Item: RePurposed Leather Armor #called Void Leathers)
Added Reputation: AMNeutralRep
Edited Faction, Interfaction Relations for:
	PBrazilKievaShiFaction
	PBrazilNCRFactionAlly
	PBrazilShiFaction
	PBrazilSurvivalistFriend
	PlayerFaction
	RaiderFaction
	TeammateFaction
		#I need to configure that to its most optimital with added ArchMagus Factions
Made Script: 
	AMVoidDISGWarning 
		- Edit this script to accomodate "ArchMagusWarnings" likely?
	ArchMagArmorBreak
	- "ArchMagArmorBreak" #To be utilized when speaking with Nos, Silverman or Captain Jackson (raider who kidnaps in pinehaven -- will use ArchMagusWarningACTUNEQUIP Message -- )
	ArchMagusWarningEquipScript (need to add OnEquip; and if statement)
	ArchMagusWarningAddScript (need to add OnGrab AMArmorLeather; and if statement)
	ArchMagusWarningUnEquipScript (need to add an Unequip script; and if statement)
Edited Scripts:
	DisguiseFactionPulseScript
	DisguiseFactionQuestScript

Added Message:
	ArchMagusWarningAdd
	ArchMagusWarningEquip
	ArchMagusWarningUnEquip
	ArchMagusWarningACTUNEQUIP

When it's done. Everything will be updated and names changed will reflect the mod (PBAMAG?), I will say. Prior to this, I had no experience with GECK unless you count adding a "book" to Oblivion some years back when I was probably... twelve? 

11/1/2018
	- RED INVALID TEXTURE TRIANGLES -- It could be a GOG problem but it shoulds red exclamations texture wise, but I don't remember messing with anything. Only adding the leathers to the world? I'll try placing it in a container to see if it fixes the problem.

As of now, 11/1/2018, the AMVoidDISGWarning script:
	- Activates upon picking up item, I need to change the pickup text to "This could be an effective disguise." Need to make an "ArchMagusWarningScript", I think. 
	- When equipping, make it say "You are now disguised."; it shouldn't mess with other faction relations aside from the "dummy" faction.
	- Fix the mesh, texture issues when sharing the archive with someone else (RED INVALID TEXTURE/MESH TRIANGLES)

As of 11/2/2018
		- Added Messages, Warning Scripts. Still need to edit AMVoidDISGWarning Script