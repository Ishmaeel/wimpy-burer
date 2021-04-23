
Wimpy Burer addon for Call of Pripyat **Gunslinger** mod. Not compatible with vanilla or any other mods.

# Installation
* Just copy the gamedata, Rico. You know what to do.
* If you get a conflict with `gunsl_overrides.xml`, keep your own version, this one just contains a minor bonus for the attentive. It's not important.
* If you get conflicts with any other files, you're going to have to merge the changes.

# Changes
* Burer's gravi attack was too fast and too deadly. It was impossible to dodge in most situations.
  - Gravi attack shockwave speed nerfed significantly.
  - Gravi attack damage nerfed slightly, so it's not a one-shot kill.
  - Burer no longer uses gravi attack at point-blank range. 
  - Extended gravi attack range to compensate. (It's too easy to dodge at long range, tho.)

* Burer does not actualy have a shitload of health, but its damage resistance was very high.
  - Nerfed burer damage resistance very slightly. Two barrels of buckshot in the face should be enough to kill one. One barrel should not.
  
* Telekinesis attack is an aimbot / one-shot kill in most cases even behind cover. I failed to lower the speed or damage of thrown objects.
  - Settled with deeply nerfing the manipulated object count from 4 to 1. This should give a stalker some non-zero chance of survival.

* Disarm attack (which sapped stamina) was immensely powerful. 
  - Heavily nerfed stamina damage from the disarm attack, so a stalker should be able to survive the first attack without losing their weapon.
  
* Burer does not actually have infinite shield, but the shield never goes into cooldown.
  He will keep it for a very long time if he feels threatened and also put it up again immediately after lowering it for a fast attack.
  How long he will keep the shield up is related to how much threatened he feels by his attacker and this is related to the weapon held by the stalker.
  You will notice he is more reluctant to lower his shield when you are holding something strong like a gauss rifle.
  If you are holding a crappy PM, he will get cockier and will drop his shield more frequently to use his attacks. 
  - Slightly increased burer's risk threshold. He should now cower behind his shield for a shorter duration.

* Depriving burer from a short range gravi attack left him kinda helpless, so,
  - Somewhat buffed burer's standing claw attack to keep his lawyer's mouth shut.
  
* He also played mind games, shaking the view and splashing blood on screen when he wasn't even dealing damage, so,
  - Disabled some of his cosmetic viewport animations which didn't make sense.

* Three burers in the Laboratory X-8 were practically invincible as long as the player was outside their room. 
  - Removed the specific scripting that heals them on hit.

* Three burers in the same area means multiple flying objects triangulating your exact coordinates for instakill fun.
  - Took away telekinesis ability from one of the Lab X-8 burers. He was dropped on his head as a baby.
  - Another X-8 burer can now only handle smaller objects. He has been neglecting his mental gymnastics.
  - The remaining X-8 burer now has significantly softer skin and lower armor. No reason, just out of spite.

# Final Notes
I wasn't able to do most of the things I wanted to do with the burer, because either the engine ignores some values in the config files,
or I'm wildly misinterpreting what they are for. In any case, I wasn't able to modify his shield behavior or his telekinesis attack the way
I wanted to. I had to settle with values that seem to give a stalker a few more strategies with which to deal with him. Assault rifles are
still not a good way to engage these dwarves, but short-range strategies with shotguns (or even a Desert Eagle) should be viable now.

I may have made him too easy because I suck as a player but I can say that even though I can consistently kill him now, he is still able
to pwn me if I get cocky or careless. If that balance does not work for you, I hope you can further tweak my values to find one that will.

These tweaks were made against a sunrise suit and a TOZ-34 shotgun. An exoskeleton will probably make this fight far too easy. Oh well. 

Good hunting.