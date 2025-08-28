# KTG's Open Air Seed Market

This is a Content Patcher pack that adds a new location map where you can buy seeds without time restrictions, as well as fertilizers, sprinklers, and more!

# What it is

Presently working, there are shops for Flowers, Seasonal Crops (one shop for each season), Special Crops (like mixed seeds and pine cones), and Tools (so you can get iridium sprinklers and deluxe fertilizers right from the start). A Dairy shop has just been added, intended for cooks to get their hands on normal quality milk, eggs, and cheese without having to keep animals.

# What it is NOT

I'm not going to try to mess around with the seed price values, or rebalancing economies, or any of that. I barely managed to get the map working, dang it!

That said, there were seeds that had no default prices, and so I matched the vanilla base game prices from the other shops where you can get them. Those seeds were: 

- Mixed Crop Seeds (30g, to match Krobus's shop prices)
- Mixed Flower Seeds (30g to match the crop version)
- Strawberry Seeds (100g to match the Spring Festival prices)
- Cactus Seeds (150g to match Sandy's Shop)

I have no idea if my price setting for these seeds will override any rebalancing mods, but it should only happen at the Seed Market Shops. If you happen to write those kinds of mods, and have specific suggestions (preferably with example code included) for any fixes that would make my little seed market work better with your mod, I am open to looking it over. 

# Dependencies

- Content Patcher - this is a content pack for that framework
- Central Station (optional) - so you can get to the Market without having to walk there
- Farm Type Manager (optional) - for forage
- SMAPI - so your mods work, at all

# Planned Development

- Farm Type Manager content pack for the map
- adding a seasonal goods vendor, and maybe another for animal produce so cooks can get cooking right from the get go

# Known Oddities and Issues

- When a shop has no inventory, there is no reaction to trying to interact with it. This happens when the option to limit the shops to season appropriate wares is set to `true`.
- Using context tags and "do not repeat" settings to get Cornucopia seeds in the shop is causing warnings about null items in the shop. Investigating whether this is an ignorable issue (and how to get rid of the underlying situ causing the warnings, regardless).
- toggling the ability to walk from the bus stop to the market while the game is loaded has no effect. 

# Think you can do this better?

This map is heavily inspired by a map that has since been taken down from Nexus, which was titled Farmer's Market, created by NotAGardener. Their idea for a seed market map worked for me, and when they took it down, I thought, hey, a chance to figure out making my own maps! 

Many head thunks later, using just the base game assets and learning from the examples I could scavenge around the net, I put together this small little outdoor map with seed vendors and some trees. 

So, if you think you can do it better, go ahead! Please! In fact, send me a link should you post your take! 

All the image assets I've used are from the base game, and I'm just following the formula for a content pack laid out by the authors of C. 

# Changelog
## 0.1.6-beta (in progress)
- removed files no longer being used
-- the tilesheet Craftables.png was swapped out for springobjects.png
- cleaned up some tiles on the map that were "alwaysFront" which really shouldn't have been
- cleaned up folder structure
## 0.1.5-beta
- Begining changelog on ReadMe.md
- added in dairy vendor
- added in a ticket machine on the map instead of relying on Central Station to keep one there
-- Testing if this resolves ticket machine vanishing when on the map and editing config
- adding in a [Farm Type Manager](https://github.com/Esca-MMC/FarmTypeManager) content pack to add foragables to the map (because I still can't figure out how to do that with content patcher >.<)




