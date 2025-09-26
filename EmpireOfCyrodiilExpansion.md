# Empire of Cyrodiil Expansion Documentation

This documentation covers the comprehensive Empire of Cyrodiil faction system, featuring the main Imperial faction and the Imperial Legion subfaction with an authentic rank progression system based on Elder Scrolls lore.

## Overview

The Empire of Cyrodiil expansion introduces **2 distinct Imperial factions** with a comprehensive rank and trait system:

### Empire of Cyrodiil (Main Faction)
- **Scope**: All Elder Scrolls races can be citizens
- **Philosophy**: Unity through diversity, bringing civilization to all peoples
- **Leadership**: Imperial administration with representation from all races
- **Tech Level**: Medieval

### Imperial Legion (Subfaction)
- **Scope**: Sentient races (excluding Dragons and certain non-humanoid beasts)
- **Philosophy**: Professional military force maintaining Imperial authority
- **Leadership**: Military hierarchy based on Roman legions
- **Tech Level**: Medieval

## Faction System

### Empire of Cyrodiil
The main Imperial faction represents the political and cultural entity of the Empire. All Elder Scrolls races can be citizens, reflecting the Empire's inclusive approach to governance.

**Allowed Races:**
- **Human Races**: Imperial, Breton, Nord, Redguard
- **Mer Races**: Altmer, Bosmer, Dunmer, Orsimer, Dwemer, Falmer, Ayleid, Chimer, Maormer, Aldmer
- **Beast Races**: All Khajiit breeds, all Argonian subraces, Lilmothiit, KaPoTun, TangMo, Tsaesci, Lamia, Imga
- **Monstrous Races**: Sload, Ogre, Goblin, Dreugh, Centaur, Giant
- **Half-Races**: HalfDunmer

### Imperial Legion
The military subfaction with restrictions based on practical military considerations.

**Allowed Races:**
- All human and mer races
- Humanoid beast races (excludes quadrupedal Khajiit forms and non-humanoid Argonians)
- Intelligent monstrous races capable of military service
- **Excluded**: Dragons (too powerful/independent), non-humanoid forms

## Imperial Legion Rank System

Based strictly on canonical Elder Scrolls ranks from Morrowind and Skyrim, organized into two distinct branches with proper hierarchy.

### Branch 1: Standard Legionary Forces
1. **Recruit** - New enlistees undergoing basic training
2. **Spearman** - Basic infantry trained in formation combat
3. **Trooper** - Standard legionnaires competent in all basic skills
4. **Agent** - Intelligence and investigation specialists
5. **Champion** - Elite warriors, pinnacle of standard legionary forces

### Branch 2: Order of Knights (Higher ranking than legionary forces)
6. **Knight Errant** - Newly commissioned knights beginning their journey
7. **Knight Bachelor** - Established knights who have proven their worth
8. **Knight Protector** - Senior knights protecting Imperial interests
9. **Knight of the Imperial Dragon** - High-ranking knights under the Dragon banner
10. **Knight of the Garland** - Highest knighthood rank, honored with the Garland

### Supreme Leadership
11. **Legate** - Regional commanders of Legion forces (from Skyrim)
12. **Commander of the Imperial Legion** - Supreme faction leader

### Support Personnel
13. **Auxiliary** - Militia and support personnel (from Skyrim)

## Trait System

The Imperial Legion features a restructured trait system organized into distinct branches that reflect the canonical Elder Scrolls hierarchy.

### Imperial Legion Legionary (Branch 1: Standard Forces)
- **Focus**: Traditional military progression through legionary ranks
- **Skills**: Melee, Shooting, Construction, Social (progressive increases)
- **Bonuses**: Combat effectiveness, mental resilience, work efficiency
- **Progression**: Recruit → Spearman → Trooper → Agent → Champion (5 degrees)

### Imperial Legion Knight (Branch 2: Order of Knights - Higher Status)
- **Focus**: Elite knighthood with noble bearing and advanced combat skills
- **Skills**: High Social and Intellectual skills, superior combat abilities
- **Bonuses**: Superior social impact, trade benefits, research bonuses, enhanced combat
- **Progression**: Knight Errant → Knight Bachelor → Knight Protector → Knight of the Imperial Dragon → Knight of the Garland (5 degrees)

### Imperial Legion Leadership (Supreme Command)
- **Focus**: Regional and supreme military command
- **Skills**: Mastery across all skill areas with emphasis on leadership
- **Bonuses**: Legendary combat stats, supreme leadership, enhanced mobility
- **Progression**: Legate → Commander of the Imperial Legion (2 degrees)

### Imperial Legion Auxiliary (Support Personnel)
- **Focus**: Support roles and militia assistance
- **Skills**: Basic combat and construction skills
- **Bonuses**: Work efficiency, basic mental resilience
- **Progression**: Single tier - Auxiliary

## Lore Accuracy

The Imperial Legion system now strictly adheres to canonical Elder Scrolls lore:

### Canonical Rank Structure
- **Morrowind Ranks**: All 10 canonical Imperial Legion ranks from Morrowind are included exactly as they appear in the game
- **Skyrim Integration**: Includes Legate (regional commander) and Auxiliary (militia support) from Skyrim
- **Two-Branch System**: Separates standard legionary forces from the prestigious knightly order, reflecting the hierarchical nature shown in lore
- **Supreme Leadership**: Commander of the Imperial Legion represents the highest canonical authority

### Removed Non-Canonical Elements
- **Roman-Specific Ranks**: Removed Centurion, Optio, Primus Pilus, Tribune, Quaestor, Praefect, Praetor (Roman military ranks not present in Elder Scrolls)
- **Modern Military Ranks**: Removed General, Field Marshal (anachronistic for Elder Scrolls setting)
- **Roman Standards**: Removed Signifer, Aquilifer (Roman standard-bearer positions not in Elder Scrolls lore)

### Authentic Hierarchy
- **Standard Forces**: Recruit through Champion represent the traditional legionary path
- **Knightly Order**: Five degrees of knighthood (Errant, Bachelor, Protector, Imperial Dragon, Garland) reflect medieval-fantasy nobility
- **Clear Separation**: Knights outrank standard legionaries, maintaining proper social hierarchy
- **Faction Leadership**: Commander of the Imperial Legion as the ultimate authority below the Emperor

### Racial Inclusivity
- **Empire Philosophy**: Reflects the Empire's inclusive approach to citizenship
- **Military Pragmatism**: Legion restrictions based on practical military needs
- **Lore Consistency**: Aligns with established faction relationships and restrictions

## Technical Implementation

### File Structure
```
Defs/
├── FactionDefs/
│   └── ImperialFactions.xml           # Empire of Cyrodiil and Imperial Legion
├── RankDefs/RankDefs_Imperial/
│   └── RankDefs_ImperialLegion/
│       └── RankDefs_ImperialLegion.xml # 13 canonical legion ranks in two branches
└── TraitDefs/
    └── ImperialLegionRanks.xml        # 4 trait categories representing branches
```

### Integration Notes
- **Standard Format**: All definitions use RimWorld XML standards
- **Balanced Progression**: Trait bonuses scale appropriately with rank
- **Exclusion System**: Prevents multiple legion ranks on same character
- **Biostat Complexity**: Higher ranks have appropriate rarity factors

### Compatibility
- **Existing Systems**: Integrates with current faction and trait systems  
- **Cultural Traits**: Compatible with existing Imperial cultural traits
- **Race System**: Works with all implemented Elder Scrolls races
- **Mod Framework**: Follows established mod patterns and conventions

## Usage

### Faction Assignment
Characters can be assigned to either the Empire of Cyrodiil (civilian) or Imperial Legion (military) factions based on their role and background.

### Rank Progression
Legion members can advance through the trait system, gaining access to higher degrees that provide better bonuses and reflect increased authority and experience.

### Roleplay Opportunities
The system provides extensive roleplay opportunities:
- **Military Campaigns**: Legion members can lead military operations
- **Imperial Administration**: Empire citizens can engage in governance
- **Cross-Cultural Unity**: All races working together under Imperial banner
- **Rank Recognition**: Social status and mechanical benefits from military service

This expansion significantly enhances the Imperial faction experience while maintaining authentic Elder Scrolls lore and balanced gameplay mechanics.