# Elder Scrolls Birth Sign System Documentation

This documentation covers the Elder Scrolls birth sign system implementation for The Multiverse Mod, providing authentic astrological traits and adult backstories from the Elder Scrolls universe.

## Overview

The Elder Scrolls Birth Sign System adds:

- **13 distinct birth signs** as optional traits reflecting The Elder Scrolls constellations
- **22 adult backstories** representing classic Elder Scrolls character classes
- **Race-specific application** limited to Elder Scrolls races only
- **Lore-accurate characteristics** for each sign and backstory

## Implemented Birth Signs

### Guardian Signs
1. **The Warrior** - Enhanced combat abilities and physical prowess
2. **The Mage** - Natural magical abilities and enhanced mental faculties  
3. **The Thief** - Stealth, agility, and dexterous skills

### Charges of the Warrior
4. **The Lady** - Enhanced social abilities and natural grace
5. **The Steed** - Enhanced speed and endurance
6. **The Lord** - Enhanced durability and natural leadership

### Charges of the Mage
7. **The Apprentice** - Natural magical affinity with vulnerability to magic
8. **The Atronach** - Massive magical potential with regeneration limitations
9. **The Ritual** - Connection to spiritual realm and undead

### Charges of the Thief
10. **The Lover** - Enhanced charm and social abilities
11. **The Shadow** - Stealth mastery and darkness abilities
12. **The Tower** - Lock-picking abilities and enhanced security skills

### Serpent Sign
13. **The Serpent** - Poison resistance and venomous abilities

## Adult Backstories

The system includes 22 classic Elder Scrolls character classes:

### Combat Classes
- **Warrior** - Professional fighter and mercenary
- **Knight** - Noble warrior bound by chivalry
- **Barbarian** - Wild tribal fighter
- **Crusader** - Holy warrior dedicated to fighting evil
- **Archer** - Skilled marksman and hunter
- **Assassin** - Deadly killer from the shadows

### Magic Classes
- **Mage** - Scholar of the arcane arts
- **Sorcerer** - Natural magical ability user
- **Battlemage** - Warrior-scholar combining combat and magic
- **Spellsword** - Warrior augmenting martial skill with magic
- **Healer** - Dedicated practitioner of healing arts
- **Witchhunter** - Hunter of dark magic practitioners

### Stealth Classes
- **Thief** - Master of stealth and larceny
- **Rogue** - Criminal underworld survivor
- **Agent** - Covert operative and spy
- **Nightblade** - Shadow fighter combining stealth and magic
- **Acrobat** - Nimble performer and entertainer

### Social Classes
- **Bard** - Traveling entertainer and storyteller
- **Pilgrim** - Devout traveler to sacred sites
- **Monk** - Contemplative warrior with spiritual discipline
- **Scout** - Expert tracker and wilderness guide

## Technical Implementation

### File Structure

```
Defs/
├── TraitDefs/
│   └── ElderScrollsBirthSigns.xml    # Birth sign trait definitions
├── BackstoryDefs/
│   └── ElderScrollsAdultBackstories.xml # Adult backstory definitions
└── PawnKindDefs/
    ├── PawnKind_HumanRaces.xml       # Updated with ElderScrolls category
    ├── PawnKind_MerRaces.xml         # Updated with ElderScrolls category
    ├── PawnKind_BeastRaces.xml       # Updated with ElderScrolls category
    ├── PawnKind_ArgonianSubraces.xml # Updated with ElderScrolls category
    └── PawnKind_Dunmer.xml           # Updated with ElderScrolls category
```

### Birth Sign Traits

- **Commonality**: Set to 0.08 for balanced distribution
- **Conflicting Traits**: All birth signs conflict with each other (one per character)
- **Skill Bonuses**: Range from +1 to +5 based on lore accuracy
- **Stat Modifiers**: Authentic Elder Scrolls sign effects

### Backstory System

- **Spawn Categories**: Limited to "ElderScrolls" category
- **Race Application**: Applied through PawnKindDef backstoryCategories
- **Skill Focus**: Each backstory emphasizes appropriate skills
- **Work Restrictions**: Some backstories have required/disallowed work types

## Gameplay Impact

### Character Generation
- Elder Scrolls race characters have chance to spawn with birth signs
- Adult backstories provide lore-appropriate character backgrounds
- Each sign provides meaningful bonuses without overpowering gameplay

### Balance Considerations
- Birth signs provide moderate bonuses (+1 to +5 skill levels)
- Stat modifiers are balanced for meaningful impact
- Conflicting traits ensure only one birth sign per character
- Low commonality prevents birth sign saturation

## Lore Accuracy

The system faithfully represents Elder Scrolls lore:

- **Authentic Signs**: All 13 canonical birth signs from the series
- **Lore-Accurate Effects**: Sign bonuses match Elder Scrolls game mechanics
- **Classic Classes**: Backstories represent iconic Elder Scrolls character archetypes
- **Race Specificity**: Only applies to races from the Elder Scrolls universe

## Usage

Players will encounter:
- Elder Scrolls colonists with authentic backstories and birth signs
- Meaningful character specializations based on astrological influences
- Rich roleplay opportunities through lore-accurate character backgrounds
- Balanced gameplay that enhances rather than dominates the experience

The birth sign system adds significant depth to Elder Scrolls character creation while maintaining game balance and authentic lore representation.