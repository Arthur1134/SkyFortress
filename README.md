# Sky Fortress Ultimate

Pixel shoot-em-up (shmup): stages, bosses, hangar unlocks, graze, charge shot, bombs, meta upgrades.

## Play

Open `index.html` or the [GitHub Pages](https://arthur1134.github.io/SkyFortress/) build.

## Controls

Arrow keys / WASD · Space/Z fire (hold to charge) · X/B bomb · P pause · M music · R slow-mo · V volume

## What's new in 0.2.0

- Larger integer-scaled play view (up to 6×) with a clearer bezel
- Splash screen, polished menus / How to Play / Hangar
- Richer FX: explosions, sparks, muzzle flash, score/combo/graze popups, multi-layer parallax
- Clearer enemy vs player bullets; boss phase banners, telegraph, defeat burst
- Snappier movement, stronger charge/bomb feedback, mid-boss variety, fairer pacing

## Version

Bump `GAME_VERSION` in `index.html` and `version.json` together when shipping.


## Stages (v0.3.0)

1. **Dawn Patrol** — open sky
2. **Cave Run** — tunnel / stalactites
3. **Neon City** — skyline flyover
Then cycles storm, desert, night, arctic, volcanic. Stages are much longer.

## Stages (v0.3.0)

1. **Dawn Patrol** — open sky
2. **Cave Run** — tunnel with stalactites / floating rocks
3. **Neon City** — skyline flyover with lit windows
Then storm, desert, night, arctic, volcanic. Stages are much longer.


## Bosses (v0.3.2)
Each stage has a unique boss (Dawn Gunship, Cave Mech Bat that dives at you, Neon Tower, Storm Carrier, Sand Scarab, Shadow Raider, Ice Breaker, Magma Wyrm). Bosses have much higher HP.


## Dev options (remove before publish)
Options → Unlimited health is a playtest god mode stored in `sf_settings`. Strip `godMode` before marketplace release.
