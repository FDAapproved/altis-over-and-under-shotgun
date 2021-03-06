# Altis O/U Shotgun
 A weapon addon for the gzdoom gameplay mod 'Hideous Destructor'.
 Sourced from [Gollgagh's O/U shotgun.](https://forum.zdoom.org/viewtopic.php?t=59120)
# Compat
This add-on requires bullet-lib (the Hideous Destructor ammunition library) to function.
# Features
This mod includes the following modules:
```
- Altis Shotgun (weapon),
- Altis O/U Menu (see GZDoom options), 
	+ spawn rate and user cvars contained within.
```
# CVARS
```
ous_weapon_spawn_bias, 4,  "1 in 5"
- (set to 0 to replace all, -1 to disable),
ous_slug_chance_bias,  4,  "1 in 5"
- (set to 0 to replace all, -1 to disable),
ous_unique_slug_noise, false
- (set to true to use a unique slug sound),
ous_slayer_hud,        false
- (set to true to use a hud akin to the slayer's). 
```
# Weapon Description
```
Name:           "Altis" over-and-under shotgun,
Role:           Mid/Long Range Suppression, Shield Breaking,
Bulk:           150 blocks,
Held Mass:      7,
Length:         30 (1 while breach is open),
Ammunition:     12 gauge (buck, slugs),
Refid:          ous,
Configurations:
- ochoke, uchoke - 0-7, 0 skeet, 7 full,
- oslug, uslug   - 0-1, 0 shell, 1 slug,
- aslug,         - 0-1, oslug + uslug,
Quirks:
- doubled accuracy,
- does not auto-eject unspent shells,
- retains doublefire from the slayer,
- can slamfire,
- breach can be closed by movement momentum. 
```
## Description:
 The Altis is intended as a slow and accurate alternative to the Slayer doublebarreled shotgun, and is ideally used from well defended positions. Unlike the Slayer, the Altis has manual, partial reloads, allowing the shooter to mix ammunition types, or choose to load only the over/under barrels. 
## Field Notes:
 When loaded with only slugs, the Altis nearly depletes a Hell-Knight's shields with one doubleshot. The increased accuracy of the Altis makes buckshot especially deadly against squishy targets from longer ranges.
