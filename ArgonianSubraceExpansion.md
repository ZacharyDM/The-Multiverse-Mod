# Argonian Subrace Expansion Documentation

## Overview

This expansion introduces **6 distinct Argonian subraces** based on Elder Scrolls lore, each with unique traits, appearances, and cultural roles. Additionally, it includes **7 Argonian factions**, comprehensive apparel and weapon systems, and architectural styles that reflect the rich culture of Black Marsh.

## Argonian Subraces

### Saxhleel (Standard Argonians)
- **Heritage**: The most common subrace, traditional marsh-dwellers
- **Key Traits**: Superior disease resistance, natural healing, deep Hist connection
- **Skill Bonuses**: Medicine +4, Animals +3, Plants +2, Social +1
- **Special Abilities**: Enhanced immunity gain, toxin resistance, temperature adaptation
- **Lore**: The quintessential Argonians connected to the Hist trees

### Naga (Serpentine Argonians)
- **Heritage**: Large, serpentine Argonians with powerful tails
- **Key Traits**: Enhanced physical strength, swimming abilities, reduced land mobility
- **Skill Bonuses**: Melee +4, Medicine +3, Mining +2, Construction +2
- **Special Abilities**: Increased melee damage, carrying capacity, slower movement
- **Lore**: Powerful warriors and laborers with snake-like features

### Sarpa (Humanoid Argonians)
- **Heritage**: More humanoid proportions, enhanced intellect
- **Key Traits**: Superior social skills, diplomatic abilities, research aptitude
- **Skill Bonuses**: Intellectual +4, Social +3, Medicine +2, Artistic +2
- **Special Abilities**: Enhanced research speed, negotiation, trade prices
- **Lore**: Natural diplomats and scholars among Argonian society

### Agaceph (Chameleon Argonians)
- **Heritage**: Chameleon-like with color-changing abilities
- **Key Traits**: Natural camouflage, stealth mastery, ambush tactics
- **Skill Bonuses**: Shooting +4, Medicine +2, Animals +2, Melee +2
- **Special Abilities**: Enhanced accuracy, hit chance, psychic sensitivity
- **Lore**: Master scouts and assassins, perfect for stealth operations

### Paatru (Toad-like Argonians)
- **Heritage**: Robust, toad-like builds with exceptional endurance
- **Key Traits**: Incredible constitution, toxin resistance, work capacity
- **Skill Bonuses**: Mining +5, Construction +4, Medicine +3, Plants +2
- **Special Abilities**: Enhanced work speed, immunity gain, mental resilience
- **Lore**: Natural laborers and builders, backbone of Argonian society

## Argonian Factions

### An-Xileel
- **Type**: Nationalist Organization
- **Goal**: Drive non-Argonians from Black Marsh
- **Specialty**: Guerrilla warfare, Hist connection
- **Relations**: Hostile to outsiders

### Shadowscales
- **Type**: Assassin Guild
- **Goal**: Serve Argonian interests through stealth
- **Specialty**: Assassination, stealth operations
- **Relations**: Hidden, neutral to most

### Hist Keepers
- **Type**: Religious Order
- **Goal**: Protect and commune with Hist trees
- **Specialty**: Healing, spiritual guidance
- **Relations**: Peaceful, welcoming

### Black Marsh Trading Company
- **Type**: Merchant Consortium
- **Goal**: Trade Black Marsh resources
- **Specialty**: Commerce, exotic goods
- **Relations**: Friendly, trade-focused

### Root-Whisper Tribe
- **Type**: Traditionalist Tribe
- **Goal**: Preserve ancient ways
- **Specialty**: Traditional knowledge, Hist communion
- **Relations**: Isolationist but not hostile

### Thornscale Clan
- **Type**: Warrior Tribe
- **Goal**: Serve as mercenaries and protectors
- **Specialty**: Combat, intimidation
- **Relations**: Neutral, mercenary

### Glade Runners
- **Type**: Scout Organization
- **Goal**: Patrol Black Marsh borders
- **Specialty**: Tracking, reconnaissance
- **Relations**: Protective, territorial

## Apparel System

### Traditional Equipment
- **Hist-Bark Armor**: Sacred wood armor with natural protection
- **Hist-Bark Helmet**: Traditional head protection
- **Marsh Walker Boots**: Specialized swamp footwear
- **Hist Communion Robes**: Sacred vestments for religious ceremonies

### Specialized Gear
- **Shadowscale Armor**: Stealth-focused leather armor
- **Thornscale War Paint**: Ritualistic intimidation markings

Each piece provides appropriate stat bonuses and reflects the cultural identity of different Argonian groups.

## Weapon System

### Traditional Weapons
- **Hist-Wood Spear**: Sacred wood spear with natural toxin resistance
- **Marsh Bow**: Recurved bow designed for swamp conditions
- **Hist Communion Staff**: Magical focus for spiritual leaders

### Specialized Weapons
- **Shadowscale Dagger**: Curved, toxin-coated assassin blade
- **Naga War Club**: Heavy weapon for serpentine warriors

All weapons are crafted using traditional materials and provide bonuses appropriate to their cultural role.

## Building Styles

### Architectural Categories
1. **Saxhleel Traditional**: Organic curves, Hist integration
2. **An-Xileel Militant**: Fortified, camouflaged structures
3. **Shadowscale Hidden**: Concealed, secretive architecture
4. **Hist Keeper Sacred**: Living tree integration, spiritual sanctuaries
5. **Thornscale Warrior**: Intimidating, spike-adorned buildings
6. **Glade Runner Scout**: Lightweight, elevated observation posts
7. **Root-Whisper Ancient**: Primitive but sophisticated techniques

## Technical Implementation

### File Structure
```
Defs/
├── RaceDefs/
│   └── ArgonianSubraces.xml           # 5 Argonian subrace definitions
├── TraitDefs/
│   └── ArgonianSubraceTraits.xml      # Unique traits for each subrace
├── FactionDefs/
│   └── ArgonianFactions.xml           # 7 Argonian factions
├── ThingDefs/
│   ├── Apparel/
│   │   └── ArgonianApparel.xml        # 6 unique apparel items
│   ├── Weapons/
│   │   └── ArgonianWeapons.xml        # 5 unique weapons
│   ├── Races/
│   │   └── MorrowindAnimals.xml       # Wamasu beast definition
│   └── Items/
│       └── MorrowindAnimalIngredients.xml # Wamasu hide material
├── StyleCategoryDefs/
│   ├── ArgonianStyles.xml             # 7 architectural styles
│   ├── ArgonianApparelStyles.xml      # Apparel style categories
│   ├── ArgonianWeaponStyles.xml       # Weapon style categories
│   └── ArgonianBuildingStyles.xml     # Building style categories
└── PawnKindDefs/
    ├── PawnKind_ArgonianSubraces.xml  # Argonian subrace spawning
    └── PawnKind_MorrowindAnimals.xml  # Wamasu beast spawning
```

## Integration Notes

- All definitions use standard RimWorld XML format
- Compatible with existing Elder Scrolls races expansion
- Balanced stat bonuses for meaningful progression
- Authentic Elder Scrolls lore representation
- Comprehensive cultural and aesthetic systems

## Lore Accuracy

The expansion faithfully represents Elder Scrolls lore by:
- Using canonical Argonian subrace names and characteristics
- Implementing authentic faction dynamics
- Reflecting the cultural importance of the Hist trees
- Representing the diverse ecology of Black Marsh
- Maintaining the mysterious and adaptable nature of Argonian society
- **Correctly placing Wamasu as separate beasts rather than Argonian subraces, as per Elder Scrolls lore**

This creates a rich, immersive experience that captures the essence of Argonian culture while providing diverse gameplay options through the various subraces and their unique abilities. The Wamasu appear as dangerous beasts native to the swamps of Black Marsh, maintaining their lore-accurate status as separate creatures rather than a subrace of Argonians.