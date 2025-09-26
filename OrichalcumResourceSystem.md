# Orichalcum Resource System Implementation

This document describes the implementation of the Orichalcum resource system as an exclusive Orsimer faction technology.

## Overview

This implementation adds **Orichalcum** as an extremely rare legendary metal exclusive to Orsimer factions:

- **Orichalcum**: Legendary sacred metal with divine properties
- **Orsimer-Only Technology**: Requires quest completion and faction relationships
- **Ultra-Rare Mining**: Even rarer than Ebony with minimal yields
- **Sacred Crafting**: High skill requirements and expensive processing

## Resources Created

### Orichalcum
- **Market Value**: 1200 gold per unit (2x Ebony price)
- **Description**: Sacred golden-green metal blessed by Malacath
- **Properties**: Legendary beauty and divine crafting applications
- **Rarity**: Ultra-rare (even more rare than Ebony)
- **Uses**: Raw material for the finest possible equipment

### Orichalcum Ingot
- **Market Value**: 2000 gold per unit
- **Description**: Refined sacred metal using Orsimer techniques
- **Material Stats**: 4.5x hit points, 2.8x sharp damage, 2.5x blunt damage
- **Crafting Material**: Superior to all other materials in the game
- **Requirements**: Requires Orsimer Sacred Metallurgy research

## Mining Availability

Orichalcum can be found extremely rarely in mountainous regions:

### Spawn Locations
- **Extreme Desert**: 0.001 spawn weight (legendary rarity)
- **Ashlands**: 0.001 spawn weight (legendary rarity)
- **Molag Amur**: 0.0005 spawn weight (mythical rarity)

### Mining Properties
- **Yield**: 3 units per deposit (very low)
- **Drop Chance**: 40% (challenging extraction)
- **Durability**: 1200 hit points (hardest to mine)

## Orsimer-Exclusive Technology

### Research Requirements
1. **Orsimer Sacred Metallurgy** (5000 research points)
   - Prerequisite: Smithing
   - Unlocks basic orichalcum processing
   - Requires establishing trust with Orsimer factions

2. **Orsimer Master Crafting** (7500 research points)
   - Prerequisite: Orsimer Sacred Metallurgy + Complex Clothing
   - Unlocks advanced orichalcum techniques
   - Enables creation of legendary equipment

### Quest Integration
- Research projects represent completing sacred trials with Orsimer strongholds
- Technology cannot be obtained without faction relationships
- Maintains lore-accurate exclusivity of Orsimer metallurgical secrets

## Faction Trading

Only Orsimer factions sell Orichalcum:

### Orsimer Special Resource Traders
- **Orichalcum**: 1200-3000 gold total stock value
- **Access**: Available through all Orsimer stronghold factions
- **Exclusivity**: No other factions trade this resource

### Supported Factions
- Iron Orcs (mountain metalworkers)
- Mor Khazgur (weapon masters)
- Narzulbur (mining specialists)

## Processing System

### Basic Processing Recipe
- **Input**: 5 Orichalcum + 10 Gold + 2 Industrial Components
- **Output**: 2 Orichalcum Ingots
- **Requirements**: Crafting skill 16, Orsimer Sacred Metallurgy research
- **Work**: 4800 work units (very time consuming)

### Master Processing Recipe
- **Input**: 3 Orichalcum + 8 Gold + 3 Jade + 1 Industrial Component
- **Output**: 3 Orichalcum Ingots (more efficient)
- **Requirements**: Crafting skill 18, Orsimer Master Crafting research
- **Work**: 6000 work units (extremely demanding)

## Building Materials

### Orichalcum Structures
- **Orichalcum Walls**: 750 hit points, +25 beauty
- **Orichalcum Blocks**: Superior building material with 4x beauty multiplier
- **Smoothed Orichalcum**: Natural walls with divine radiance

## Balance Considerations

- **Extreme Rarity**: Spawn rates ensure this remains the rarest resource
- **High Skill Requirements**: Crafting 16-18 needed for processing
- **Expensive Processing**: Requires gold, jade, and industrial components
- **Faction Dependence**: Cannot progress without Orsimer relationships
- **Legendary Performance**: Stats justify the extreme investment required

## Requirements Fulfilled

✅ **Extremely rare mineable resource**: Spawn rates 5-10x rarer than Ebony  
✅ **Orsimer-only trading**: Exclusive to Orsimer faction traders  
✅ **Orsimer-only technology**: Research gated behind faction relationships  
✅ **Quest-enabled technology**: Research represents completing sacred trials  
✅ **Lore integration**: Follows Elder Scrolls tradition of sacred Orcish metals  
✅ **Superior properties**: Best material stats in the game  

## File Structure

```
Defs/
├── ThingDefs/Items/
│   └── OrichalcumResources.xml         # Resource and ingot definitions
├── ThingDefs/Buildings/
│   ├── MineableVolcanicRocks.xml       # Mineable deposit (updated)
│   └── VolcanicRockBuildings.xml       # Building materials (updated)
├── RockTypeDefs/
│   └── VolcanicRocks.xml               # World generation (updated)
├── ResearchProjectDefs/
│   └── OrsimerTechnology.xml           # Sacred metallurgy research
├── RecipeDefs/
│   └── OrsimerMetallurgyRecipes.xml    # Processing recipes
└── TraderKindDefs/
    └── SpecialResourceTraders.xml      # Orsimer traders (updated)
```

This implementation creates a complete Orichalcum system that fulfills all requirements while maintaining balance and lore consistency with the existing Elder Scrolls-themed mod content.