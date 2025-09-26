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

Based on the Morrowind Imperial Legion ranks with additional authentic ranks from other Elder Scrolls games and Roman military tradition.

### Entry Level Ranks
1. **Recruit** - New enlistees undergoing basic training
2. **Spearman** - Basic infantry trained in formation combat
3. **Trooper** - Standard legionnaires competent in all basic skills

### Specialist Ranks
4. **Agent** - Intelligence and investigation specialists
5. **Champion** - Elite warriors serving as examples to others

### Non-Commissioned Officers
6. **Sergeant** - Squad leaders and trainers
7. **Centurion** - Century commanders (80-100 soldiers)
8. **Optio** - Centurion's second-in-command
9. **Primus Pilus** - Senior centurion, most experienced NCO

### Commissioned Officers  
10. **Knight** - Commissioned officers granted knighthood
11. **Captain** - Company commanders (100-200 soldiers)
12. **Tribune** - Strategic commanders of multiple centuries

### Senior Command
13. **Quaestor** - Administrative officers handling logistics
14. **Praefect** - Regional military commanders
15. **Praetor** - Military magistrates with civilian authority
16. **Legate** - Legion commanders (thousands of soldiers)

### Supreme Command
17. **General** - Multi-legion commanders
18. **Field Marshal** - Theater commanders, highest rank below Emperor

### Special Positions
19. **Signifer** - Standard-bearers maintaining unit cohesion
20. **Aquilifer** - Elite standard-bearers carrying the golden eagle

## Trait System

The Imperial Legion features an upgradable trait system that provides progressive benefits as characters advance through the ranks.

### Imperial Legion Recruit
- **Focus**: Basic military training and discipline
- **Skills**: Melee +1, Shooting +1, Construction +1
- **Bonuses**: Slight mental resilience improvement
- **Progression**: Entry-level trait for new legionnaires

### Imperial Legion Enlisted
- **Focus**: Trained infantry skills and basic military competence
- **Skills**: Melee +2-3, Shooting +2-3, Construction +2, Social +1
- **Bonuses**: Combat accuracy, mental resilience
- **Progression**: Spearman → Trooper (2 degrees)

### Imperial Legion Specialist
- **Focus**: Specialized roles requiring advanced training
- **Skills**: Variable based on specialization (Agent vs Champion)
- **Bonuses**: Role-specific bonuses (investigation vs combat)
- **Progression**: Agent → Champion (2 degrees)

### Imperial Legion Non-Commissioned
- **Focus**: Leadership and tactical command
- **Skills**: Social +4-5, balanced combat and technical skills
- **Bonuses**: Leadership abilities, combat effectiveness, work efficiency
- **Progression**: Sergeant → Centurion (2 degrees)

### Imperial Legion Commissioned
- **Focus**: Officer leadership and strategic thinking
- **Skills**: High social and intellectual skills, strong combat abilities
- **Bonuses**: Superior social impact, trade benefits, combat effectiveness
- **Progression**: Knight → Captain (2 degrees)

### Imperial Legion Senior
- **Focus**: Strategic command and regional authority
- **Skills**: Exceptional across all areas, emphasis on leadership and intellect
- **Bonuses**: Research speed, superior combat and social abilities
- **Progression**: Tribune → Legate (2 degrees)

### Imperial Legion Supreme
- **Focus**: Grand strategic command and theater operations
- **Skills**: Mastery across all skill areas
- **Bonuses**: Legendary combat stats, supreme leadership, enhanced mobility
- **Progression**: General → Field Marshal (2 degrees)

### Imperial Legion Special Position
- **Focus**: Specialized roles with unique responsibilities
- **Skills**: Role-specific skill distributions
- **Bonuses**: Position-specific benefits (morale, honor, experience)
- **Progression**: Signifer → Aquilifer → Primus Pilus (3 degrees)

## Lore Accuracy

The Imperial Legion system faithfully represents Elder Scrolls lore:

### Morrowind Foundation
- **Rank Names**: Based directly on Morrowind Imperial Legion ranks
- **Progression**: Follows the established advancement system
- **Cultural Integration**: Reflects the Legion's role in Morrowind

### Cross-Game Integration
- **Additional Ranks**: Incorporates ranks from Oblivion, Skyrim, and ESO
- **Roman Influence**: Maintains the historical Roman military inspiration
- **Authentic Terminology**: Uses proper Latin military terms where appropriate

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
│       └── RankDefs_ImperialLegion.xml # 20 distinct legion ranks
└── TraitDefs/
    └── ImperialLegionRanks.xml        # 6 progressive trait categories
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