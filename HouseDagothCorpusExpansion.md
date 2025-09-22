# House Dagoth Corpus Expansion Documentation

This documentation covers the House Dagoth corpus expansion, featuring corpus monsters, the Corpus disease, and faction alignment mechanics based on The Elder Scrolls III: Morrowind lore.

## Overview

House Dagoth represents the corrupted and transformed remnants of the lost Great House, centered around the divine disease known as Corpus. This expansion introduces:

### Corpus Creatures
- **Dreamers** - Corpus-touched prophets and seers with enhanced psychic abilities
- **Ash Vampires** - Elite corpus warriors transformed into immortal champions
- **Corpus Stalkers** - Corpus-twisted scouts and infiltrators
- **Sleepers** - Those under Dagoth Ur's spell who undergo progressive corpus transformation
- **Corpus Touched** - General corpus affliction affecting various individuals

### Corpus Disease
A divine disease that transforms the flesh of the infected, providing:
- **Benefits**: Enhanced immunity, toxin resistance, and unique abilities
- **Drawbacks**: Gradual physical and mental degradation, social stigma
- **Progression**: Four stages from minor to extreme symptoms
- **Transmission**: Contracted through serious injuries from corpus creatures

### Expanded Rank System
House Dagoth now includes corpus-specific ranks alongside traditional house ranks:

**Traditional Ranks (0-10):**
- 0. Hireling
- 1. Retainer  
- 2. Oathman/Oathwoman
- 3. Lawman/Lawwoman
- 4. Kinsman/Kinswoman
- 5. House Cousin
- 6. House Brother/Sister
- 7. House Father/Mother
- 8. Councilman/Councilwoman
- 9. House Councilor
- 10. Grandmaster

**Corpus-Specific Ranks:**
- **Corpus Initiate** - Beginning corpus transformation
- **Corpus Adept** - Mastery of corpus techniques
- **Dream Priest/Priestess** - Interpreter of divine dreams
- **Ash Priest/Priestess** - Overseer of corpus rituals
- **Corpus Lord/Lady** - Advanced corpus transformation leader
- **Ash Vampire Lord/Lady** - Elite immortal champion
- **Visionary Master/Mistress** - Highest ranking dreamer
- **Sleeper Tender** - Overseer of sleeper transformation
- **Ash Master/Mistress** - Commander of transformed ash beings
- **Ascended Commander** - Elite ascended sleeper with command authority

## Trait System

Each corpus creature type has associated traits with progressive power levels:

### Dreamers
- **Focus**: Psychic abilities, visions, and divine guidance
- **Skills**: Intellectual, Artistic, Social, Medicine
- **Bonuses**: Psychic sensitivity, learning speed, negotiation
- **Drawbacks**: Mental instability, reality distortion
- **Progression**: Dream-Touched → Dream Prophet → Master Dreamer

### Ash Vampires
- **Focus**: Supernatural combat prowess and corpus mastery
- **Skills**: Melee, Shooting, Medicine, Social
- **Bonuses**: Enhanced speed, combat accuracy, armor rating
- **Special**: Near-immortal champions with divine powers
- **Progression**: Lesser → Standard → Greater Ash Vampire

### Corpus Stalkers
- **Focus**: Stealth, reconnaissance, and hunting
- **Skills**: Shooting, Animals, Plants, Melee
- **Bonuses**: Movement speed, stealth, accuracy
- **Drawbacks**: Reduced social impact due to disturbing appearance
- **Progression**: Corpus Scout → Corpus Stalker

### Sleepers
- **Focus**: Progressive corpus transformation and servitude to Dagoth Ur
- **Skills**: Melee, Medicine, Mining, Construction, Shooting, Intellectual (at higher levels)
- **Bonuses**: Enhanced durability, work speed, combat abilities, corpus resistance
- **Drawbacks**: Severe social penalties, mental instability, loss of free will
- **Progression**: Sleeper → Ash Slave → Ash Zombie → Ash Ghoul → Ascended Sleeper

### Corpus Touched
- **Focus**: Early corpus infection and adaptation
- **Skills**: Medicine
- **Bonuses**: Disease immunity, toxin resistance
- **Drawbacks**: Social stigma and gradual degradation
- **Progression**: Single tier - Corpus Touched

## Corpus Disease Mechanics

The Corpus hediff represents the divine disease central to House Dagoth lore:

### Transmission
- Contracted through serious injuries from corpus creatures
- Cannot be cured through conventional medicine
- Considered a "divine blessing" by House Dagoth members

### Disease Stages
1. **Minor (0-0.39)**: Basic immunity boost, slight movement penalty
2. **Moderate (0.4-0.69)**: Enhanced immunity, consciousness impact
3. **Major (0.7-0.84)**: Strong immunity, significant capability loss
4. **Extreme (0.85-0.95)**: Maximum immunity, life-threatening symptoms

### Disease Progression
- Progresses at 0.02 severity per day
- Cannot be stopped or cured conventionally
- Provides increasing benefits and penalties over time

## Player Faction Alignment

Players can align with House Dagoth under specific conditions:

### Alignment Requirements
- Must possess corpus-related traits or hediffs
- Requires completion of House Dagoth questlines
- May require specific corpus transformation events
- Alignment affects relationships with other factions

### Alignment Benefits
- Access to corpus-specific equipment and abilities
- Unique corpus transformation opportunities
- Special House Dagoth rank progression
- Corpus creature allies and followers

### Alignment Consequences
- Hostility from Tribunal Temple and Imperial forces
- Social penalties with non-corpus affiliated NPCs
- Gradual corpus transformation over time
- Potential conflict with other Great Houses

## Lore Accuracy

This expansion faithfully represents House Dagoth from The Elder Scrolls III: Morrowind:

### Canonical Elements
- Corpus as a divine disease granted by Dagoth Ur
- Ash Vampires as elite immortal champions
- Dreamers as corpus-touched prophets and seers
- The transformative nature of corpus infection
- House Dagoth's role as a corrupted Great House

### Thematic Integration
- Corpus as both blessing and curse
- Divine disease mechanics reflecting Morrowind lore
- Progressive transformation and power escalation
- Social stigma and factional conflicts
- The duality of corpus benefits and costs

## Integration Notes

- All definitions use standard RimWorld XML format
- Traits provide skill bonuses using the base game system
- Hediff mechanics follow RimWorld disease patterns
- Stat offsets balanced for meaningful progression
- Multiple trait degrees allow character development
- Corpus disease uses chronic hediff mechanics

## File Structure

```
Defs/
├── HediffDefs/
│   └── CorpusDisease.xml           # Corpus disease definition
├── TraitDefs/
│   └── HouseDagothCorpus.xml       # Corpus creature traits
└── RankDefs/RankDefs_Dunmer/RankDefs_Dagoth/
    └── RankDefs_Dagoth.xml         # Expanded House Dagoth ranks
```

This structure maintains compatibility with existing House Dagoth content while adding comprehensive corpus-related mechanics that reflect the transformative and corrupting nature of the divine disease in Elder Scrolls lore.

## Quest Integration Potential

The corpus system is designed for quest integration:
- Corpus infection events and transformation rituals
- House Dagoth alignment through corpus acceptance
- Progressive corruption and power acquisition
- Conflicts between corpus and traditional Dunmer society
- Divine visions and prophetic questlines through Dreamers