## 0.3.0 (09/03/2026)
### New Content
- New combat art: Verdant Echo (Wave Melee Lv.1A)
- Added Fae Stream support for Verdant Echo clones
### Changes
- Palm Basher (vanilla placeholder) changed to Wave Attack Lv.2A for now
- Non-neutral "ballTrail" effects for charged default projectiles CHANGE_SCALE increased from 1.1 to 1.15
- Fae Stream is no longer dash-cancelable during the first 0.2 seconds while projectiles are being shot
### Fixes
- Fixed excess spaces after effect src file paths

## 0.2.0 (09/03/2026)
### New Content
- New combat art: Fae Stream (Wave Throw Lv.1A)
- Added effect spritesheet lighter-particle-big-pentagon.png
- Added effect spritesheet penta-misc.png
- Added specials effect files
### Changes
- Default uncharged projectiles now use "noLightGlow": false
- Default melee attack reduced delay before finisher by 0.01 seconds

## 0.1.0 (09/02/2026)
### New Content
- Created effect file combat.pentafistXPC
- Created penta "ball" effect files
### Changes
- Charged default projectiles now use custom trail effects
- Charged default projectiles now have "light": S
- Uncharged default projectiles now have "light": S
- Default melee attacks:
  * Overhaul: Default melee attacks combo forever and automatically do a finisher when inputs are stopped
  * Unified element-specific ATTACK/ATTACK_REV/ATTACK_FINISHER actions into single BASE actions
  * Reduced speed during melee attacks from 200 to 160
  * ATTACK and ATTACK_FINISHER are now identical
  * MOVE_TO_DIR changed to "stopBeforeEdge": false
  * Increased size of default punch effects (combat.pentafistXPC) to pScale 1.15
  * Increased size of finisher punch effects (combat.pentafistXPC) to pScale 1.3
  * Punch effects (combat.pentafistXPC) are now cancelable, have sound variance, and emit light
### Balance
- Default DASH action is now quicker and has reduced travel duration
- Default melee attacks:
  * Now utilizes SPAWN_ASSAULT, with base strength 0.5
  * Default punch hitbox radius increased from 40 to 44
  * Action block "action" increased from 0.15 to 0.175
  * Attack damageFactor decreased from 0.7 to 0.55
  * ATTACK_REV now has MEDIUM knockback, others have LIGHT
  * Attack zHeight inreased from 0 to 16
  * Finisher punch now uses damageFactor 0.8 and SPAWN_ASSAULT 1.0

## 0.0.2 (08/20/2026)
- Updated spritesheet layout

## 0.0.1 (08/20/2026)
- Initial Release
- Player file created from Emilie2 with Big Punch Test added
- Grayed out spritesheets with placeholder animations