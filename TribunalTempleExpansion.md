# Tribunal Temple Expansion Documentation

This documentation covers the expanded Tribunal Temple faction system, featuring specialized orders that can be held independently and combined like noble titles.

## Overview

The Tribunal Temple expansion introduces multiple specialized branches within the Temple hierarchy:

### Ordinator Orders
- **Order of the Watch** - Temple guardians and peacekeepers
- **Order of War** - Military wing focused on warfare and combat
- **Order of Doctrine and Ordination** - Scholars, teachers, and lorekeepers  
- **Order of Inquisition** - Investigators and heresy hunters
- **High Ordinators** - Elite temple guards above all other orders
- **Hands of Almalexia** - Ultimate guardians chosen by the Healing Mother

### Buoyant Armigers
- Elite warrior-mystics specializing in combating dark forces
- Progressive ranks from Aspirant to Grand Marshal

## Trait System

Each order has an associated trait that provides progressive skill bonuses and stat improvements:

### Order of the Watch
- **Focus**: Defense, construction, vigilance
- **Skills**: Melee, Shooting, Construction
- **Bonuses**: Hit chance, dodge chance, shooting accuracy
- **Progression**: Watchman → Senior Watchman

### Order of War  
- **Focus**: Combat excellence and military leadership
- **Skills**: Melee, Shooting, Medicine, Social
- **Bonuses**: Damage, hit chance, armor rating
- **Progression**: War Priest → Champion of War

### Order of Doctrine and Ordination
- **Focus**: Knowledge, teaching, research
- **Skills**: Intellectual, Social, Medicine, Artistic
- **Bonuses**: Learning factor, research speed, trade improvement
- **Progression**: Temple Scholar → Master of Doctrine

### Order of Inquisition
- **Focus**: Investigation, negotiation, judgment
- **Skills**: Social, Intellectual, Shooting
- **Bonuses**: Trade improvement, negotiation ability
- **Progression**: Inquisitor → Grand Inquisitor

### High Ordinators
- **Focus**: Elite combat and leadership
- **Skills**: Melee, Shooting, Social, Construction
- **Bonuses**: Exceptional combat stats, armor rating
- **Progression**: High Ordinator → High Ordinator Captain

### Hands of Almalexia
- **Focus**: Supernatural abilities and divine favor
- **Skills**: All major skills with high bonuses
- **Bonuses**: Extreme combat stats, movement speed, immunity
- **Progression**: Single tier - Hand of Almalexia

### Buoyant Armigers
- **Focus**: Anti-supernatural warfare and mental resilience
- **Skills**: Melee, Shooting, Intellectual, Medicine
- **Bonuses**: Mental break resistance, combat effectiveness
- **Progression**: 5 tiers from Initiate to Grand Marshal

## Rank System

Each order has its own independent rank progression that can be combined with others:

### Combinable Titles
Like the royalty system, pawns can hold multiple ranks simultaneously:
- A pawn could be both a "High Ordinator Captain" and "Champion Armiger"
- Ranks from different orders stack and complement each other
- This represents the complex hierarchy and cross-training in the Temple

### Quest Integration
The system is designed to be quest-linked and unlockable:
- Traits can be gained through specific questlines
- Rank progression tied to accomplishments and story events  
- Reflects the player's journey through Temple hierarchy

## Lore Accuracy

All ranks and abilities are based on canonical Morrowind lore:

### Ordinator Orders
Based on the various branches mentioned in Elder Scrolls lore, each with distinct roles and specializations within the Temple hierarchy.

### Buoyant Armigers
Elite warrior-monks known for their battles against daedra and supernatural threats, with the Grand Marshal as their ultimate leader.

### Power Progression
The system scales from basic temple members to legendary figures like the Hands of Almalexia, who possess near-divine abilities.

## Integration Notes

- All definitions use standard RimWorld XML format
- Traits provide skill bonuses using the same system as the base game
- Stat offsets are balanced to provide meaningful progression without breaking gameplay
- Multiple trait degrees allow for character development over time

## File Structure

```
Defs/
├── TraitDefs/
│   ├── TribunalTempleOrders.xml    # 5 Ordinator order traits
│   └── BuoyantArmigers.xml         # Buoyant Armiger progression
└── RankDefs/RankDefs_Dunmer/RankDefs_TribunalTemple/Orders/
    ├── OrderOfTheWatch.xml
    ├── OrderOfWar.xml  
    ├── OrderOfDoctrineAndOrdination.xml
    ├── OrderOfInquisition.xml
    ├── HighOrdinators.xml
    ├── HandsOfAlmalexia.xml
    └── BuoyantArmigers.xml
```

This structure allows for easy expansion and modification while maintaining clear separation between different order systems.