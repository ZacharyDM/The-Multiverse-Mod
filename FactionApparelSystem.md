# Faction-Specific Apparel System Documentation

This documentation covers the comprehensive faction-specific apparel system added to The Multiverse Mod, providing unique armor and clothing for different factions and subfactions based on The Elder Scrolls III: Morrowind lore.

## Overview

The apparel system adds **20+ unique apparel items** across multiple faction categories:

### Tribunal Temple Orders (7 items)
- **Order of the Watch Armor** - Blue and gold armor for temple guardians
- **Order of War Armor** - Heavy combat armor for warrior-priests
- **Order of Doctrine Robes** - Scholarly robes for temple scholars
- **Order of Inquisition Armor** - Dark intimidating armor for investigators
- **High Ordinator Armor** - Elite golden armor for supreme temple guards
- **Hands of Almalexia Armor** - Legendary divine armor with supernatural properties
- **Buoyant Armiger Armor** - Specialized armor for anti-supernatural combat

### Ashlander Clans (8 items)
- **Ahemmusa Clan Robes** - Peaceful, wisdom-focused garments
- **Urshilaku Clan Garments** - Traditional prophecy-keeper clothing
- **Erabenimsun War Garb** - Battle-ready warrior clan attire
- **Zainab Trader Garments** - Fine diplomatic and trading clothes
- **Kagesh Ritual Robes** - Mysterious arcane-marked robes
- **Ulath Shadow Garments** - Stealth-focused survival gear
- **Vereansu Spirit Robes** - Ancestral spirit-connected sacred robes
- **Mabrigash Warrior Robes** - Matriarchal mystical combat robes

### Great Houses (5 items)
- **House Redoran Armor** - Martial crab-shell design armor
- **House Hlaalu Robes** - Elegant merchant-diplomat clothing
- **House Telvanni Robes** - Mystical sorcerer robes with magical properties
- **House Indoril Armor** - Sacred ceremonial temple guardian armor
- **House Dres Garments** - Practical agrarian overseer clothing

### House Dagoth Corpus (4 items)
- **Sleeper Robes** - Corpus-afflicted tattered garments
- **Ash Vampire Armor** - Corrupted supernatural elite armor
- **Corpus Stalker Gear** - Stealth-focused scouting equipment
- **Corprus Beast Hide** - Crude but protective creature hide armor

## Mechanical Features

### Stat Bonuses
Each apparel item provides appropriate stat bonuses reflecting the faction's characteristics:
- **Combat-focused factions** get accuracy, damage, and armor bonuses
- **Scholarly factions** get research speed and learning bonuses
- **Trade-focused factions** get negotiation and social impact bonuses
- **Stealth-focused factions** get movement speed and accuracy bonuses
- **Mystical factions** get psychic sensitivity and mental break resistance

### Material Requirements
- **Light Robes**: 45-90 fabric
- **Medium Armor**: 110-140 metallic materials
- **Heavy Armor**: 150-200 metallic materials
- **Specialized Gear**: Various fabric/leather combinations

### Tech Level Integration
- **Neolithic**: Basic Ashlander clothing
- **Medieval**: Great House and Temple armor
- **Industrial**: Elite Temple armor
- **Spacer/Ultratech**: Legendary divine armor

## File Structure

```
Defs/ThingDefs/Apparel/
├── TribunalTemple/
│   ├── OrdinatorArmor.xml      # Basic order armor
│   └── EliteArmor.xml          # High-tier elite armor
├── Ashlanders/
│   ├── MainClanApparel.xml     # Four main clan garments
│   └── AdditionalClanApparel.xml # Four additional clan garments
├── GreatHouses/
│   └── GreatHouseApparel.xml   # All five Great House items
└── HouseDagoth/
    └── CorpusApparel.xml       # Corpus-influenced gear

Textures/Things/Pawn/Humanlike/Apparel/
├── TribunalTemple/            # Temple order textures
├── Ashlanders/               # Ashlander clan textures
├── GreatHouses/              # Great House textures
└── HouseDagoth/              # House Dagoth corpus textures
```

## Integration Notes

- All definitions use standard RimWorld XML format
- Apparel items are tagged by faction for easy outfit assignment
- Stat bonuses align with existing trait systems for each faction
- Research prerequisites match appropriate technology levels
- Crafting requirements scale with item power level

## Lore Accuracy

The apparel system faithfully represents Elder Scrolls lore:
- **Visual Design**: Each faction's traditional colors and symbols
- **Material Culture**: Appropriate materials and crafting methods
- **Social Hierarchy**: Armor quality reflects rank and status
- **Cultural Identity**: Items reinforce faction characteristics and values

## Usage

Players can:
1. Craft faction-specific apparel at appropriate crafting stations
2. Assign outfits to colonists based on their faction alignment
3. Use apparel as rewards or quest items in faction storylines
4. Display faction loyalty through distinctive clothing choices

This system significantly enhances faction identity and provides meaningful progression rewards for players engaging with The Elder Scrolls universe within RimWorld.