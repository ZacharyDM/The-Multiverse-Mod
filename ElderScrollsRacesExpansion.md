# Elder Scrolls Races Expansion Documentation

This documentation covers the addition of 9 main Elder Scrolls races to The Multiverse Mod, providing authentic racial characteristics and abilities from the Elder Scrolls universe.

## Overview

The Elder Scrolls Races expansion introduces **9 playable races** organized into **3 categories**:

### Human Races (4 races)
- **Breton** - Magic-resistant scholars from High Rock
- **Nord** - Hardy warriors from Skyrim  
- **Redguard** - Desert warriors from Hammerfell
- **Imperial** - Diplomatic empire-builders from Cyrodiil

### Mer Races (3 races)
- **Bosmer** - Forest archers from Valenwood
- **Altmer** - Magical supremacists from Summerset
- **Orsimer** - Berserker smiths from Orsinium

### Beast Races (2 races)
- **Khajiit** - Feline traders and thieves from Elsweyr
- **Argonian** - Reptilian healers from Black Marsh

## Racial Characteristics

### Breton
- **Heritage**: Mixed human-elven ancestry from High Rock
- **Key Traits**: Natural magic resistance, enhanced intellect
- **Skill Bonuses**: Intellectual +3, Medicine +2, Social +1
- **Special Abilities**: Reduced psychic sensitivity, lower mental break threshold
- **Lore**: Known for their natural resistance to magic and scholarly pursuits

### Nord  
- **Heritage**: Hardy humans adapted to Skyrim's harsh climate
- **Key Traits**: Exceptional cold resistance, natural warriors
- **Skill Bonuses**: Melee +3, Construction +2, Mining +1
- **Special Abilities**: Enhanced cold resistance, natural armor bonus
- **Lore**: Fierce independent warriors known for their strength and building skills

### Redguard
- **Heritage**: Desert-dwelling warriors from Hammerfell
- **Key Traits**: Superior combat abilities, heat adaptation
- **Skill Bonuses**: Melee +3, Shooting +2, Mining +1
- **Special Abilities**: Enhanced heat resistance, improved melee accuracy
- **Lore**: Considered the most naturally talented warriors in Tamriel

### Imperial
- **Heritage**: Diplomatic empire-builders from Cyrodiil
- **Key Traits**: Natural leadership, commercial acumen
- **Skill Bonuses**: Social +3, Intellectual +2, Artistic +1
- **Special Abilities**: Better trade prices, enhanced negotiation
- **Lore**: The diplomatic core of the Empire with natural charm and leadership

### Bosmer (Wood Elf)
- **Heritage**: Forest-dwelling elves bound by the Green Pact
- **Key Traits**: Unmatched archery skills, nature connection
- **Skill Bonuses**: Shooting +4, Animals +2, Plants +2
- **Special Abilities**: Enhanced shooting accuracy, increased movement speed
- **Lore**: Master archers who live in harmony with nature

### Altmer (High Elf)
- **Heritage**: Magically superior elves from Summerset
- **Key Traits**: Enhanced magical abilities, intellectual superiority
- **Skill Bonuses**: Intellectual +4, Artistic +2, Crafting +1
- **Special Abilities**: Faster research, increased psychic sensitivity
- **Lore**: Consider themselves the most civilized and magically gifted race

### Orsimer (Orc)
- **Heritage**: Transformed elves known for strength and honor
- **Key Traits**: Exceptional physical strength, smithing mastery
- **Skill Bonuses**: Melee +4, Crafting +3, Mining +2
- **Special Abilities**: Increased melee damage, faster work speed
- **Lore**: Honor-bound society focused on strength and craftsmanship

### Khajiit
- **Heritage**: Feline humanoids with varied forms
- **Key Traits**: Natural agility, stealth abilities, keen senses
- **Skill Bonuses**: Animals +2, Melee +2, Crafting +1, Medicine +1
- **Special Abilities**: Enhanced movement speed, improved work efficiency
- **Lore**: Nomadic traders and skilled thieves with natural feline grace

### Argonian
- **Heritage**: Reptilian people connected to the Hist trees
- **Key Traits**: Disease resistance, natural healing, swamp adaptation
- **Skill Bonuses**: Medicine +3, Animals +2, Plants +1
- **Special Abilities**: Faster immunity gain, improved temperature tolerance
- **Lore**: Mysterious lizard-folk with deep connection to nature and healing

## Technical Details

### Base Templates
- **HumanBase**: Standard human characteristics with 80-year lifespan
- **MerBase**: Extended elven characteristics with 200-year lifespan (existing)
- **BeastRaceBase**: Enhanced beast race characteristics with 90-year lifespan

### Racial Traits System
Each race has a unique trait providing:
- Skill bonuses reflecting their cultural specializations
- Stat modifiers for gameplay balance
- Lore-appropriate abilities and resistances

### File Structure

```
Defs/
├── RaceDefs/
│   ├── HumanBase.xml          # Template for human races
│   ├── BeastRaceBase.xml      # Template for beast races
│   ├── HumanRaces.xml         # Breton, Nord, Redguard, Imperial
│   ├── BeastRaces.xml         # Khajiit, Argonian
│   └── MerRaces.xml           # Bosmer, Altmer, Orsimer
├── TraitDefs/
│   ├── ElderScrollsRacialTraits.xml     # Human/Beast race traits
│   └── ElderScrollsMerRacialTraits.xml  # Mer race traits
└── PawnKindDefs/
    ├── PawnKind_HumanRaces.xml # Human race spawning
    ├── PawnKind_BeastRaces.xml # Beast race spawning
    └── PawnKind_MerRaces.xml   # Mer race spawning
```

## Integration Notes

- All definitions use standard RimWorld XML format
- Traits provide skill bonuses using the base game system
- Stat offsets are balanced for meaningful progression without breaking gameplay
- Racial characteristics reflect authentic Elder Scrolls lore
- Compatible with existing mod components and systems

## Texture Requirements

The expansion expects texture files at the following paths (textures not included in code):
- `UI/Icons/ThingCategories/HumanBase.png`
- `UI/Icons/ThingCategories/BeastRaceBase.png`
- `UI/Icons/ThingCategories/Breton.png`
- `UI/Icons/ThingCategories/Nord.png`
- `UI/Icons/ThingCategories/Redguard.png`
- `UI/Icons/ThingCategories/Imperial.png`
- `UI/Icons/ThingCategories/Khajiit.png`
- `UI/Icons/ThingCategories/Argonian.png`
- `UI/Icons/ThingCategories/Bosmer.png`
- `UI/Icons/ThingCategories/Altmer.png`
- `UI/Icons/ThingCategories/Orsimer.png`

Additional textures may be needed for:
- Race-specific portraits and body graphics
- Faction-specific racial variations
- Age-specific appearances

## Gameplay Impact

### Balance Considerations
- Each race has distinct advantages and disadvantages
- No race is objectively superior - each excels in different areas
- Racial bonuses are meaningful but not overpowering
- Maintains compatibility with existing game balance

### Faction Integration
- Races can be integrated with existing faction systems
- Compatible with Great Houses, Tribunal Temple, and other factions
- Provides diverse recruitment options for different playstyles

### Roleplay Opportunities
- Rich lore background for each race
- Distinct cultural characteristics reflected in gameplay
- Supports varied colony compositions and strategies
- Enhances immersion in the Elder Scrolls universe

This expansion significantly enriches the Elder Scrolls experience within RimWorld by providing authentic racial diversity with meaningful gameplay differences.