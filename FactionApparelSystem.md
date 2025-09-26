# Faction-Specific Apparel System Documentation

This documentation covers the comprehensive faction-specific apparel system added to The Multiverse Mod, providing unique armor and clothing for different factions and subfactions based on The Elder Scrolls III: Morrowind lore.

## Overview

The apparel system adds **18+ unique apparel items** and **12 comprehensive style systems** across multiple faction categories:

### Tribunal Temple Orders (7 items)
- **Order of the Watch Armor** - Blue and gold armor for temple guardians
- **Order of War Armor** - Heavy combat armor for warrior-priests
- **Order of Doctrine Robes** - Scholarly robes for temple scholars
- **Order of Inquisition Armor** - Dark intimidating armor for investigators
- **High Ordinator Armor** - Elite golden armor for supreme temple guards
- **Hands of Almalexia Armor** - Legendary divine armor with supernatural properties
- **Buoyant Armiger Armor** - Specialized armor for anti-supernatural combat

### Ashlander Clans (8 style categories)
- **Ahemmusa Style** - Peaceful, wisdom-focused designs with earth-toned patterns
- **Urshilaku Style** - Traditional prophecy-keeper aesthetics with sacred symbols
- **Erabenimsun Style** - Battle-ready warrior styling with intimidating war decorations
- **Zainab Style** - Fine diplomatic designs displaying wealth and sophistication
- **Kagesh Style** - Mysterious aesthetics with arcane symbols and ritual markings
- **Ulath Style** - Stealth-focused styling with dark, concealed designs
- **Vereansu Style** - Ancestral spirit-connected aesthetics with otherworldly energy
- **Mabrigash Style** - Matriarchal mystical warrior styling with enchanted patterns

### Human Races (7 style categories)
- **Imperial Style** - General Cyrodiil sophistication with elegant designs and quality craftsmanship
- **Colovian Style** - Western Cyrodiil martial culture with earth tones and practical highland designs
- **Nibenese Style** - Eastern Cyrodiil sophistication with rich colors and magical elements
- **Imperial Legion Style** - Military organization with red and gold Legion aesthetics and disciplined designs
- **Breton Style** - Scholarly magic-resistant designs with blue and silver academic/knightly elements
- **Nord Style** - Hardy warrior aesthetics with grey and blue practical Nordic patterns
- **Redguard Style** - Desert warrior designs with brown and bronze curved weapon influences

### Great Houses (8 items)
- **Bonemould Armor** - Base traditional Dunmer armor crafted from creature shells and bones
- **Bonemould Armor (Gah-Julan Style)** - House Redoran variant with enhanced combat effectiveness
- **Bonemould Armor (Armun-an Style)** - House Hlaalu variant with diplomatic and trade bonuses
- **House Redoran Master Helmet** - Unique ceremonial helmet for the House Redoran leader
- **House Telvanni Robes** - Mystical sorcerer robes with magical properties
- **House Telvanni Cephalopod Helmet** - Distinctive helmet worn by Telvanni guards
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

### Style System Features
The Ashlander clans and human races now use RimWorld's style system, providing:
- **Comprehensive Visual Identity**: Each faction has consistent styling across apparel, weapons, and buildings
- **Flexible Application**: Styles apply to multiple item types rather than unique single items
- **Enhanced Immersion**: Complete aesthetic coherence for each faction's settlements and equipment
- **Expanded Coverage**: Styles extend beyond apparel to include weapons and architecture

### Tech Level Integration
- **Neolithic**: Basic Ashlander styles and traditional crafting
- **Medieval**: Great House and Temple armor
- **Industrial**: Elite Temple armor
- **Spacer/Ultratech**: Legendary divine armor

## File Structure

```
Defs/ThingDefs/Apparel/
├── TribunalTemple/
│   ├── OrdinatorArmor.xml      # Basic order armor
│   └── EliteArmor.xml          # High-tier elite armor
├── GreatHouses/
│   └── GreatHouseApparel.xml   # All five Great House items
└── HouseDagoth/
    └── CorpusApparel.xml       # Corpus-influenced gear

Defs/StyleCategoryDefs/
├── AshlanderStyles.xml         # 8 Ashlander clan style categories
├── AshlanderApparelStyles.xml  # Apparel styles for all 8 clans
├── AshlanderWeaponStyles.xml   # Weapon styles for all 8 clans
├── AshlanderBuildingStyles.xml # Building styles for all 8 clans
├── HumanRacialStyles.xml       # 7 human cultural style categories
├── HumanRacialApparelStyles.xml # Apparel styles for all 7 human cultures
├── HumanRacialWeaponStyles.xml # Weapon styles for all 7 human cultures
└── HumanRacialBuildingStyles.xml # Building styles for all 7 human cultures

Textures/Things/Pawn/Humanlike/Apparel/
├── TribunalTemple/            # Temple order textures
├── Ashlanders/               # Ashlander clan style textures
├── GreatHouses/              # Great House textures
├── HouseDagoth/              # House Dagoth corpus textures
└── HumanRaces/               # Human cultural style textures
    ├── Imperial/             # General Imperial sophistication
    ├── Colovian/             # Western Cyrodiil martial culture
    ├── Nibenese/             # Eastern Cyrodiil sophistication  
    ├── ImperialLegion/       # Imperial Legion military aesthetics
    ├── Breton/               # Breton scholarly-knightly style
    ├── Nord/                 # Nord hardy warrior style
    └── Redguard/             # Redguard desert warrior style

Textures/Item/Equipment/WeaponMelee/
├── Ashlander/[ClanName]/     # Weapon textures for each clan
└── HumanRaces/[CultureName]/    # Weapon textures for each human culture

Textures/Building/[Type]/
├── Ashlander/[ClanName]/     # Building textures for each clan
└── HumanRaces/[CultureName]/    # Building textures for each human culture
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
1. Apply faction-specific styles to apparel, weapons, and buildings through the style system
2. Create cohesive clan settlements with consistent visual themes
3. Craft styled items that reflect their chosen Ashlander clan affiliation
4. Build complete clan compounds with matching architecture and equipment
5. Use styled items as rewards or quest items in faction storylines
6. Display faction loyalty through comprehensive visual consistency

The style system significantly enhances faction identity by providing complete visual coherence across all aspects of clan life, from personal equipment to settlement architecture, creating a more immersive experience within The Elder Scrolls universe.