# Orsimer (Orc) Cultural Expansion Documentation

This document covers the comprehensive Orsimer expansion system, featuring distinct cultural traits, specialized factions, cultural styles, religious systems, and unique animals that reflect the rich diversity and heritage of the Orcish peoples.

## Overview

The Orsimer expansion introduces **8 distinct cultural groups** organized into **4 main categories**:

### Cultural Groups (8 groups)
- **Wood Orcs** - Forest-adapted Orcs influenced by Bosmeri culture
- **Iron Orcs** - Mountain metalworkers from the Dragontail Mountains
- **City Orcs** - Sophisticated urbanites from Orsinium
- **Stronghold Orcs** - Traditional stronghold followers of Malacath
- **Dushnikh Yal** - Armor masters specializing in defense
- **Largashbur** - Shamanic beast masters with spiritual traditions
- **Mor Khazgur** - Legendary weapon crafters
- **Narzulbur** - Master miners and ore processors

### Factions (8 factions)
- **Wood Orcs** - Forest tribes following the Green Pact
- **Iron Orcs** - Independent mountain clans
- **Orsinium** - The great Orcish city-state
- **Dushnikh Yal** - Traditional armor-focused stronghold
- **Largashbur** - Shamanic stronghold with beast mastery
- **Mor Khazgur** - Weapon-master stronghold
- **Narzulbur** - Mining-focused stronghold

## Cultural Traits System

Each cultural group has unique traits that provide specialized skill bonuses and stat improvements:

### Wood Orc Heritage
- **Skills**: Melee +3, Shooting +3, Crafting +2, Animals +2, Plants +1
- **Specialization**: Forest survival, archery, and balanced combat
- **Culture**: Blends Orcish strength with Bosmeri wisdom

### Iron Orc Heritage
- **Skills**: Crafting +5, Mining +4, Melee +3, Construction +2
- **Specialization**: Superior metalworking and rare ore processing
- **Culture**: Independent mountain metalworkers with unmatched skill

### City Orc Heritage
- **Skills**: Melee +3, Crafting +3, Social +3, Intellectual +2, Construction +2
- **Specialization**: Urban sophistication with diplomatic abilities
- **Culture**: Balanced strength and civilization

### Stronghold Orc Heritage
- **Skills**: Melee +4, Crafting +3, Mining +2, Construction +2, Social +1
- **Specialization**: Traditional warrior-smiths following ancient ways
- **Culture**: Honor-bound society following the Code of Malacath

### Dushnikh Yal Heritage
- **Skills**: Melee +4, Crafting +4, Construction +2, Mining +2
- **Specialization**: Armor mastery and defensive excellence
- **Culture**: Most traditional and disciplined stronghold

### Largashbur Heritage
- **Skills**: Melee +4, Animals +3, Medicine +2, Crafting +2, Intellectual +1
- **Specialization**: Shamanic traditions and beast mastery
- **Culture**: Spiritual connection to Malacath and nature

### Mor Khazgur Heritage
- **Skills**: Melee +5, Crafting +4, Mining +2, Shooting +1
- **Specialization**: Legendary weapon crafting and combat mastery
- **Culture**: Elite warriors and weapon smiths

### Narzulbur Heritage
- **Skills**: Mining +5, Crafting +4, Melee +3, Construction +2
- **Specialization**: Master mining and rare material expertise
- **Culture**: Deep mountain mining traditions

## Faction System

### Trade Specializations
- **Wood Orcs**: Animal trading, forest products
- **Iron Orcs**: Rare metals, superior crafted goods, animals
- **Orsinium**: Diplomatic trading, luxury goods
- **Dushnikh Yal**: Standard stronghold goods
- **Largashbur**: Animals, shamanic goods
- **Mor Khazgur**: Weapons, rare metals
- **Narzulbur**: Rare ores, mining equipment

### Leadership Structure
- **Wood Orcs**: Forest Chief
- **Iron Orcs**: Forge Master
- **Orsinium**: King of Orsinium
- **Strongholds**: Chief of [Stronghold Name]

## Cultural Style System

Each culture has unique visual styles for apparel, weapons, and buildings:

### Style Themes
- **Wood Orc**: Green and brown earth tones with organic curves
- **Iron Orc**: Dark iron and steel with angular fortress designs
- **City Orc**: Deep greens and golds with refined elegance
- **Stronghold Orc**: Rough-hewn tribal designs in earth tones
- **Dushnikh Yal**: Layered metal plates in dark greens and bronze
- **Largashbur**: Bone and hide accents with spiritual totems
- **Mor Khazgur**: Blade-like motifs in steel and dark green
- **Narzulbur**: Geometric patterns inspired by crystal formations

### Supported Items
- **Apparel**: Parka, Robe, Tunic, Collar Shirt, Flak Vest, Plate Armor
- **Weapons**: Knife, Gladius, Longsword, Mace, Spear, Bows (varied by culture)
- **Buildings**: Wall, Door, Bed, Tables, Chairs, Furniture

## Religious System

Three distinct Orsimer religious memes reflect their spiritual diversity:

### Malacath Worship (Impact: 2)
- **Focus**: Traditional Daedric Prince worship
- **Deities**: Malacath, stronghold spirits, heroic ancestors
- **Associated**: All stronghold factions
- **Worship Room**: Shrine of Malacath
- **Key Precepts**: Code of Malacath, strength through adversity

### Trinimac Worship (Impact: 2)
- **Focus**: Ancient Aedric faith seeking redemption
- **Deities**: Trinimac, aspects of divine strength
- **Associated**: City Orcs, some progressive strongholds
- **Worship Room**: Temple of Trinimac
- **Key Precepts**: Honor, redemption, divine order

### Orsimer Ancestor Worship (Impact: 1)
- **Focus**: Clan and stronghold ancestor veneration
- **Deities**: Clan founders, stronghold builders, ancestral spirits
- **Associated**: All Orsimer cultures
- **Worship Room**: Ancestor Shrine
- **Key Precepts**: Clan loyalty, tradition preservation

## Animal System

Four unique animals reflect Orsimer beast mastery and mountain adaptations:

### Echatere
- **Type**: Pack Animal
- **Description**: Giant tick-like arthropod with chitinous shell
- **Specialization**: Heavy cargo transport in harsh terrain
- **Trade Tag**: AnimalOrsimerPack
- **Market Value**: 600 silver

### Stronghold Wolf
- **Type**: War/Guard Animal
- **Description**: Large domesticated wolves bred for loyalty
- **Specialization**: Combat, hunting, and guarding
- **Trade Tag**: AnimalOrsimerWar
- **Market Value**: 350 silver

### Mountain Goat
- **Type**: Livestock
- **Description**: Hardy high-altitude adapted goats
- **Specialization**: Milk, wool, meat production
- **Trade Tag**: AnimalOrsimerLivestock
- **Market Value**: 200 silver

### Wereboar
- **Type**: War Animal
- **Description**: Massive aggressive boars with supernatural size
- **Specialization**: Combat mount and war beast
- **Trade Tag**: AnimalOrsimerWar
- **Market Value**: 800 silver

## Integration Notes

- All definitions use standard RimWorld XML format
- Traits provide skill bonuses using the same system as the base game
- Stat offsets are balanced to provide meaningful progression
- Cultural traits are mutually exclusive within the Orsimer culture group
- Religious memes integrate with existing Ideology system
- Animal trade tags enable proper faction trading
- Style systems integrate with existing apparel and building frameworks

## File Structure

```
Defs/
├── TraitDefs/
│   └── OrsimerCulturalTraits.xml       # 8 cultural trait definitions
├── FactionDefs/
│   └── OrsimerFactions.xml            # 7 faction definitions
├── MemeDefs/
│   └── OrsimerReligiousMemes.xml      # 3 religious meme systems
├── RulePackDefs/
│   └── OrsimerDeityNames.xml          # Deity name generators
├── StyleCategoryDefs/
│   ├── OrsimerStyles.xml              # 8 style categories
│   ├── OrsimerApparelStyles.xml       # Apparel style mappings
│   ├── OrsimerWeaponStyles.xml        # Weapon style mappings
│   └── OrsimerBuildingStyles.xml      # Building style mappings
├── ThingDefs/Races/
│   └── OrsimerAnimals.xml             # 4 unique animal races
├── PawnKindDefs/
│   └── PawnKind_OrsimerAnimals.xml    # Animal pawn definitions
└── TraderKindDefs/
    └── SpecialResourceTraders.xml     # Animal and resource traders

Textures/
├── Things/Pawn/Humanlike/Apparel/OrsimerRaces/
│   ├── WoodOrc/                       # Wood Orc apparel textures
│   ├── IronOrc/                       # Iron Orc apparel textures
│   ├── CityOrc/                       # City Orc apparel textures
│   ├── StrongholdOrc/                 # Stronghold Orc apparel textures
│   ├── DushnikhYal/                   # Dushnikh Yal apparel textures
│   ├── Largashbur/                    # Largashbur apparel textures
│   ├── MorKhazgur/                    # Mor Khazgur apparel textures
│   └── Narzulbur/                     # Narzulbur apparel textures
├── Item/Equipment/WeaponMelee/OrsimerRaces/
│   └── [CultureName]/                 # Weapon textures for each culture
└── Building/
    └── [CultureName]/                 # Building textures for each culture
```

## Lore Accuracy

The Orsimer expansion faithfully represents Elder Scrolls lore:
- **Cultural Diversity**: Reflects the varied Orcish societies across Tamriel
- **Stronghold Traditions**: Accurately depicts the Code of Malacath and clan structure
- **Religious Complexity**: Captures the theological tension between Malacath and Trinimac worship
- **Regional Adaptations**: Shows how Orcs have adapted to different environments
- **Animal Relationships**: Includes canonical creatures used by Orcish societies
- **Material Culture**: Reflects Orcish mastery of metalworking and rare materials