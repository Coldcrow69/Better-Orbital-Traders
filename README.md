# Better Orbital Traders

RimWorld mod by Coldcrow. A powerful re-balance of vanilla orbital traders plus eight new orbital trader types, including an orbital scrapyard that buys anything.

Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=3009866854

## Features

- Much more silver on every base game (and DLC) orbital trader
- Re-balanced base game trader stock: the bulk goods ship carries every textile and raw resource by the thousand, gold and jade included, and other ships get tweaked items and quantities
- Orbital scrapyard: buys all of your items
- Orbital ecosphere: plant and animal products, livestock, pets, uncommon wildlife, rare seeds
- Organ farm: buys and sells humans and human accessories (organs and prosthetics), plus genepacks, archite capsules, hemogen, and deathrest serum with Biotech
- Narcotics dealer: every kind of drug and medicine
- Autonomous archive: books, modded ones included, and techprints, plus tomes (Anomaly) and maps (Odyssey)
- Orbital shipbreaker (Odyssey): gravlite panels, vacstone, obsidian, shuttle engines, components, and bulk metals. Buys gravship upgrades
- Void peddler (Anomaly): bioferrite, shards, tomes, dread leather, serums, cultist gear, deadlife shells. Buys revenant spines, and void sculptures with Better Tradable Items
- Guild flagship (Odyssey): never arrives on its own. Request it from the comms console as a Guild ally for more silver than any other ship and a slice of every other ship's stock
- Odyssey: all eight ships belong to the Traders Guild. Request them from the comms console, trade and gift with them for Guild goodwill, and expect them to stay away while the Guild is hostile
- Combat Extended: the flagship stocks CE ammo, FSX, prometheum, and turrets, the shipbreaker salvages turrets, heavy ammo, and FSX, and both buy them back

Ground traders and traders from other mods are left alone.

## Requirements

- RimWorld 1.6 or 1.7
- No DLC required. DLC content only exists when that DLC is active.

## Compatibility

XML only. Safe to add or remove mid-save (land any modded trade ships first). Conflicts only with mods that also edit base game orbital trader stock. Tested alongside Call A Trader, which can summon the flagship without the Guild. Trader Ships has not been re-tested since the ships joined the Traders Guild. Combat Extended works in any load order (1.x needed this mod loaded before CE), and the CE stock lines load only when CE is active. Trading Options Continued stacks on top; its multipliers multiply these numbers. Multiplayer is untested; XML only, so nothing here should desync.

## Install

Subscribe on the Workshop, or copy the `Better Orbital Traders` folder into `RimWorld/Mods`. Load order does not matter.

## Repo layout

```
Better Orbital Traders/
  About/                      mod metadata, preview image, workshop id
  Common/Defs/TraderKindDefs/ the eight new traders (void peddler needs Anomaly, shipbreaker and flagship need Odyssey)
  Common/Patches/             Core and Royalty re-balance patches, Odyssey Traders Guild request list
  CombatExtended/Patches/     loads only with Combat Extended: ammo, FSX, prometheum, turrets on the flagship and shipbreaker
  LoadFolders.xml             points 1.6 and 1.7 at Common/, plus CombatExtended/ while CE is active
  ReadMe.txt                  full notes, FAQ, changelog (ships with the mod)
  LICENSE.txt
```

## Better series

- [Better Kibble](https://github.com/Coldcrow69/Better-Kibble)
- [Better Nutrifungus](https://github.com/Coldcrow69/Better-Nutrifungus)
- [Better Tradable Items](https://github.com/Coldcrow69/Better-Tradable-Items)

## License

MIT. See [LICENSE](LICENSE).
