# Malachite and Ebony Resource System Implementation

This document describes the implementation of the Malachite and Ebony resource system as requested.

## Overview

This implementation adds two new rare resources to The Multiverse Mod:
- **Malachite**: A replacement for traditional glass with superior magical properties
- **Ebony**: An ultra-rare volcanic metal with legendary properties

## Resources Created

### Malachite
- **Market Value**: 180 gold per unit
- **Description**: Vibrant green copper carbonate mineral, serves as glass replacement
- **Properties**: Superior clarity and arcane conductivity for magical applications
- **Rarity**: Rare (can be mined very rarely in volcanic biomes)
- **Uses**: Raw resource for magical and crafting applications

### Ebony  
- **Market Value**: 600 gold per unit
- **Description**: Extremely rare volcanic glass-metal of supernatural origin
- **Properties**: Incredible durability, magical resonance, distinctive dark luster
- **Material Stats**: 3.2x hit points, 2.1x sharp damage, 1.9x blunt damage
- **Rarity**: Ultra-rare (even rarer than Malachite)
- **Uses**: Can be used as crafting material (stuffProps enabled)

## Mining Availability

Both resources can be rarely found in volcanic biomes:

### Ashlands Biome
- Malachite deposits: 0.02 spawn weight (rare)
- Ebony deposits: 0.005 spawn weight (ultra-rare)

### Molag Amur Biome
- Malachite deposits: 0.015 spawn weight (rare) 
- Ebony deposits: 0.003 spawn weight (ultra-rare)

## Faction Trading

All resources are available for trade from three specific factions:

### Dunmer Factions
- Malachite: 300-800 gold total stock value
- Ebony: 600-1500 gold total stock value

### Dwemer Technologists
- Malachite: 400-900 gold total stock value
- Ebony: 800-2000 gold total stock value (premium pricing)

### Orsimer Strongholds (New Faction)
- Malachite: 350-850 gold total stock value
- Ebony: 700-1800 gold total stock value
- Specializes in metalworking and rare materials

## Supporting Systems

### Mineable Deposits
- `MineableMalachite`: 15 yield, 80% drop chance
- `MineableEbony`: 8 yield, 60% drop chance (harder to extract)

### Building Materials
- Malachite blocks and walls (green tinted, beautiful)
- Ebony blocks and walls (dark, very beautiful)
- Smoothed variants for both materials

### Rock Types
- Integrated into RimWorld's world generation system
- Spawn naturally in specified volcanic biomes
- Proper visual integration with terrain generation

## Implementation Details

### Files Created
- `Defs/ThingDefs/Items/MalachiteEbonyResources.xml` - Resource definitions
- `Defs/FactionDefs/OrsimerFactions.xml` - Orsimer Strongholds faction
- `Defs/ThingDefs/Buildings/MineableVolcanicRocks.xml` - Mineable deposits
- `Defs/RockTypeDefs/VolcanicRocks.xml` - World generation integration
- `Defs/TraderKindDefs/SpecialResourceTraders.xml` - Faction trading
- `Defs/ThingDefs/Buildings/VolcanicRockBuildings.xml` - Walls and blocks

### Lore Integration
- Follows Elder Scrolls lore for material properties and rarity
- Malachite serves as a superior glass substitute
- Ebony maintains its legendary status from Elder Scrolls games
- Faction associations match Elder Scrolls cultural backgrounds

## Balance Considerations

- Ebony is significantly rarer and more expensive than Malachite
- Mining yields are low to maintain rarity
- Trading prices reflect the extreme value of these materials
- Spawn rates ensure these remain special, rare resources
- Material stats provide meaningful gameplay benefits without being overpowered

## Requirements Fulfilled

✅ Glass assessment: No existing glass resources found  
✅ Glass removal: Nothing to remove  
✅ Malachite creation: Implemented as glass replacement  
✅ Rare volcanic mining: Added to Ashlands and Molag Amur  
✅ Faction trading: Available from Dunmer, Orsimer, Dwemer  
✅ Ebony creation: Implemented with superior properties  
✅ Ebony ultra-rarity: Lower spawn rates and higher prices than Malachite  
✅ Ebony faction trading: Same three factions at premium prices  
✅ Resource verification: Both confirmed as properly implemented resources  