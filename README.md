# Cataclysm-DDA-Touhou-Expansion
A CDDA expansion mod for [Touhou Professions](https://github.com/RedMisao/Cataclysm-DDA-Touhou-Mod) that various things from Touhou Project lore and fluff.

**The mod's folder goes in /data/mods/**.  Last updated for game version: 2022-12-24 experimental.

```json
This is an old and busted version of the mod. Here only for archival purposes.
There's a **lot** of stuff updated over the experimentals, that was never fixed here.
Your will experience a **bad product** if you play this version over the master_0.H or the current testing.
Open an issue if for some reason, you cannot run master_0.H or current testing, and want to play this.
```

## About the mod
This mod was inspired by the following questions:
  1) How would your [insert your favorite Touhou] survive during the apocalypse?
  2) What would the Sages do if there was an Outside World "End of the World" scenario, stacked several times upon itself, simultaneously?
  3) What would each faction (Lunarians, Tengu, Underground youkai, SDM, etc.) do, after realizing that there's no status quo anymore?

and more, but those are the most important now.

It adds a lot of stuff based on the Touhou series lore (but also the fluff).  The mod is not finished, but all things that appear ingame are functional.  Balance is not guaranteed.


## Contents
The mod includes so far:
- [New mechanics](#new-mechanics)
- [New weapons](#new-weapons), including new ammo types, magazines, gunmods, etc.
- New monsters
  - [Extinct fauna](#extinct-fauna), to hunt or be hunted by
  - [Youkai](#youkai), to be haunted by
- [Custom clothing](#new-clothing)
- [New food and recipes](#new-food-and-recipes)
- [New weather](#new-weather)
and more minor additions or changes

Additionally, there's the
- [Small planned features](#minor-milestones), and
- [Big planned features](#major-milestones)

Sadly, there's also the
- [Known bugs](#known-bugs)


## New mechanics
(New in the sense they're added to the base mod)
* Impurity (WIP).  Currently a dummy mechanic, it naturally increases over time and also by consuming "impure" stuff (which is everything edible so far).  Has no effect, except for Reisen who starts with the LUNARDIET trait and loses it after acquiring enough impurity, making her tolerant to Earthly foodstuff.


## New weapons
* Prototype weapons.  Firearms that were never sold, or even fully developed, and were forgotten over time but are very interesting anyways: ARES FMG, CEAM Mòdele 1, IDW, TKB-022P and TKB-022PM No 2.
* Old weapons.  Firearms that became obsolete (?): Kar98k, Pieper M1893, SIG 550 and 550-1, Spanish Model 1983, StG 44, SVD-63.
* Cool weapons.  Because why not, other than not being intended for civilian use?: M76 Zastava, OTs-48 and OTs-48K, PGM Hécate II, SR-3MP, VSS Vintorez, Walther WA 2000.
* MIB weapons.  MIB agents are equipped with the Standard Series Sidearm, Series 7 de-Scatterer and Series 4 re-Diffuser, plus their Neuralysers.
* Misc.  The humble Thompson Contender.


## New monsters

### Extinct fauna
* Amphibians: Eryops, Pederpes, Platyoposaurus, Prionosuchus.
* Arthropods: Aegirocassis, Anomalocaris, Arthropleura, Chasmataspis, Eusarcana, Hurdia, Jaekelopterus, Megalograptus, Meganeura, Opabinia, Pambdelurion, Parastylonurus, Sidneyia.
* Birds: Dodo, Ectopistes, Icadyptes, Moa.
* Fish: Coccosteus, Dipterus, Dunkleosteus, Holoptychius, lampreys (not actually extinct), Megamastax, Saurichthys.
* Mammals: Amphicyon, Andrewsarchus, Castoroides, Daedon, Glossotherium, Glyptodont, Herpetotherium, Megatherium, Pakicetus, Taeniolabis, Thylacine.
* Mollusks: Agoniatites, Cleoniceras, Endoceras, Michelinoceras, Paracoroniceras, Parapuzosia.
* Reptiles: Anatosuchus, Carnufex, Hesperosuchus, Ichthyosaurus, Plesiosaurus, Scutosaurus, Smilosuchus, Weigeltisaurus.
* Stem-mammals: Cotylorhynchus, Dimetrodon, Lystrosaurus.
* Theriodontia: Inostrancevia, Moschorhinus, Nochnitsa, Pristerognathus, Viatkogorgon.


### Youkai
* Cryptids and urban legends: Chupacabra, Enfield horror, Jackalope, nightcrawler, Mongolian death worm, Sasquatch, skinwalkers, squonk, Yeti, MIBs.
* Ghosts: three different female ghosts.
* Oni: lesser oni, generic oni, humanoid oni.
* Tsukumogami: animated dolls, chairs.
* Youkai: Chupacabra, Beast of Gévaudan, jinmenken, kunekune.


### New clothing
* Added world spawn data for the generic clothing of the core mod: bloomers, cheongsam dresses, Tang shirts, tai chi pants, long socks.
* Some monsters also drop wearable items.


## New food and recipes
* New kinds of meat were added: arthropod meat, bird meat, lamprey meat, and shrimplike meat.  These are harvested from the extinct fauna, including chickends dropping bird meat.
* Vegetables: Satsumaimo (sweet potatoes).
* Each of the new items have their own basic crafting, like roasted bird meat, or boiled arthropod.
* New dishes were also developed, like chicken pie, chicken soup, or paella, among several others.


## New weather
* Scarlet mist and fog.  Should happen randomly, and reduce sun intensity.


## Minor milestones
Relatively easy things to add, not in order:
* Monsters: a lot more.  Fairies, rocs, banshees, more tsukumogami, etc.
* Events: Night parade and Silence hour as weather/events that happen randomly.
* Items: 16 new items that grant various special abilities or passive bonuses were already designed but not fully implemented (see Known Bugs).
* Locations: Power spots, basically small zones of interest for the player to explore/search, where forgotten items reappear and certain monsters gather, depending on the spot type or surroundings.  A small Shinto-style shrine has been added, but it's unfinished.


## Major milestones
Relatively hard or complex things to add, not in order:
* NPCs: generic and important (includes quests and some story).  NPC implementation seems relatively simple but extremely time consuming.
  * Quests: to give short-medium term goals for the player.
  * Story: revealed mostly by the NPCs but also world events.
* Locations: Reverse-spirited away places from Gensokyo, like an abandoned Hakurei shrine.  These would go from small dungeons (say, a power spot or a haunted house), to city-sized zones (say, an underground city).  Like NPCs, adding the small locations from scratch is extremely time consuming and obtuse, thankfully a mapping tool is being developed (in the official Discord) that would **greatly** improve the process.  Adding whole new zones however, multiplies the difficulty, or is impossible in the case of new dimensions.
* An (organized) species system for both the characters and youkai.  For example, species-restricted traits like flying, percentual resistance (or weakness) to different kinds of damage, etc.


## Known bugs
* Youkai and ancient fauna presence may be (slightly) higher than intended, may not.
* Seems enchantments are broken: anything inside the `passive_effects` field from items is not working properly (e.g. a mutation is applied but the bonus from that mutation aren't).  This seems to be an issue with base CDDA.


## Spoilers

<details>
    <summary>Spoiler (1/2)</summary>
    Current profession descriptions give a initial glimpse of an underlying story. So far, a tl;dr is that certain mastermind youkai is related in some way or another to the Cataclysm, so she played her hand accordingly.  Each character would meet Gensokyan NPCs, or find items, structures or clues in the world, and continue the story from that point.  This is a long term goal after I finish adding and fixing most of the "core" mod.
    <details>
        <summary>Spoiler (2/2)</summary>
        Certain 2hu fan work matches the first D of CDDA almost perfectly
            </details>
</details>
