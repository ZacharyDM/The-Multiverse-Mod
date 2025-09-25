# Morrowind Magic System Documentation

This documentation covers the Morrowind Magic System expansion for The Multiverse Mod, bringing the six schools of magic from The Elder Scrolls III: Morrowind to RimWorld.

## Overview

The Morrowind Magic System introduces authentic magical abilities based on the six schools of magic from Morrowind. Each school offers unique abilities and playstyles, with progressive mastery levels that unlock more powerful spells.

### The Six Schools of Magic

1. **Destruction** - Offensive magic dealing elemental damage
2. **Restoration** - Healing and protective magic
3. **Illusion** - Mind manipulation and stealth magic
4. **Alteration** - Matter transmutation and physical law manipulation
5. **Conjuration** - Summoning creatures and creating bound weapons
6. **Mysticism** - Soul manipulation and dimensional magic

## Magic School Mastery System

Each school has three progressive mastery levels:

### Mastery Levels
- **Apprentice (Level 0)** - Basic spells and minor bonuses
- **Adept (Level 1)** - Intermediate spells and enhanced abilities
- **Master (Level 2)** - Advanced spells and powerful effects

### Skill Benefits
Each mastery level provides:
- **Skill bonuses** relevant to the school's focus
- **Stat improvements** that enhance magical effectiveness
- **Access to spells** appropriate to the mastery level

## Schools of Magic Details

### Destruction
*"The school of Destruction deals with harnessing the forces of fire, frost, and shock to damage and debilitate foes."*

**Focus**: Offensive combat magic
**Key Skills**: Intellectual, Shooting, Melee
**Stat Bonuses**: Shooting Accuracy, Psychic Sensitivity
**Element Types**: Fire, Frost, Shock, Drain

**Spells by Level**:
- **Apprentice**: Fire Damage, Frost Damage, Shock Damage
- **Adept**: Fireball, Drain Health
- **Master**: Disintegrate Weapon

### Restoration
*"The school of Restoration deals with healing wounds, curing diseases, and providing magical protection."*

**Focus**: Healing and protection
**Key Skills**: Medicine, Intellectual, Social
**Stat Bonuses**: Immunity Gain Speed, Psychic Sensitivity
**Specialties**: Healing, Disease Curing, Protection

**Spells by Level**:
- **Apprentice**: Heal Minor Wounds, Cure Common Disease, Restore Stamina
- **Adept**: Heal Major Wounds, Shield
- **Master**: Resurrect

### Illusion
*"The school of Illusion deals with manipulating the mind, altering perception, and controlling behavior."*

**Focus**: Mind control and stealth
**Key Skills**: Social, Intellectual, Melee
**Stat Bonuses**: Social Impact, Psychic Sensitivity
**Specialties**: Charm, Invisibility, Mind Control

**Spells by Level**:
- **Apprentice**: Charm Person, Invisibility, Light
- **Adept**: Calm Humanoid, Paralyze
- **Master**: Dominate Humanoid

### Alteration
*"The school of Alteration deals with changing the fundamental properties of objects and creatures."*

**Focus**: Transmutation and utility
**Key Skills**: Crafting, Intellectual, Construction, Mining
**Stat Bonuses**: Work Speed Global, Psychic Sensitivity
**Specialties**: Transmutation, Movement, Locks

**Spells by Level**:
- **Apprentice**: Open Lock, Transmute Metal, Water Walking
- **Adept**: Levitate, Slowfall
- **Master**: Telekinesis

### Conjuration
*"The school of Conjuration deals with summoning creatures from other planes and binding souls."*

**Focus**: Summoning and soul magic
**Key Skills**: Intellectual, Animals, Melee, Social
**Stat Bonuses**: Psychic Sensitivity, Social Impact
**Specialties**: Summoning, Bound Weapons, Soul Trap

**Spells by Level**:
- **Apprentice**: Summon Ancestral Ghost, Bound Dagger, Soul Trap
- **Adept**: Summon Scamp, Bound Sword
- **Master**: Summon Dremora

### Mysticism
*"The school of Mysticism deals with the most esoteric magical arts - teleportation, soul manipulation, and dimensional magic."*

**Focus**: Advanced magical theory
**Key Skills**: Intellectual, Artistic, Social
**Stat Bonuses**: Psychic Sensitivity, Mental Break Threshold
**Specialties**: Detection, Soul Magic, Teleportation

**Spells by Level**:
- **Apprentice**: Detect Life, Dispel Magic, Absorb Health
- **Adept**: Reflect Damage, Mark, Recall
- **Master**: Soul Burn

## Racial Magic Affinities

Different Elder Scrolls races have natural affinities for specific schools of magic:

### High Magical Aptitude Races

#### Altmer (High Elves)
- **Primary Schools**: Destruction, Illusion
- **Lore**: Considered the most magically gifted race, with natural talent for offensive and mental magic
- **Bonus**: Enhanced Psychic Sensitivity and Research Speed

#### Dunmer (Dark Elves)
- **Primary Schools**: Destruction, Mysticism
- **Lore**: Traditional masters of elemental destruction and mystical arts from Morrowind
- **Bonus**: Balanced magical and combat abilities

#### Bretons
- **Primary Schools**: Restoration
- **Lore**: Mixed elven heritage provides magic resistance and healing aptitude
- **Bonus**: Natural magic resistance with healing specialization

### Moderate Magical Aptitude Races

#### Argonians
- **Primary Schools**: Restoration, Mysticism
- **Lore**: Connection to Hist trees grants healing and mystical insight
- **Bonus**: Disease resistance and natural healing

#### Khajiit
- **Primary Schools**: Illusion
- **Lore**: Moon-blessed magic focusing on stealth and mental influence
- **Bonus**: Enhanced stealth and social manipulation

## Spell Mechanics

### Cooldown System
All spells have cooldown periods to prevent spamming:
- **Basic spells**: 30 minutes - 1.5 hours
- **Advanced spells**: 2-4 hours  
- **Master spells**: 6-20 hours
- **Ultimate spells**: 24+ hours (Resurrect)

### Spell Effects
Many spells create temporary hediff effects:
- **Buff effects**: Enhanced abilities, protections, movement
- **Debuff effects**: Paralysis, charm, damage over time
- **Utility effects**: Light sources, detection, transmutation

### Targeting
Spells have different targeting requirements:
- **Self-cast**: Affects only the caster
- **Single target**: Affects one chosen target
- **Area effects**: Affects multiple targets in range
- **Location-based**: Can target ground locations

## Integration with Existing Systems

### Compatibility
The magic system integrates seamlessly with:
- **Existing Elder Scrolls races** - Natural magic affinities
- **Faction systems** - House allegiances and religious orders
- **Trait progression** - Works alongside other trait systems
- **Combat mechanics** - Magic abilities enhance combat options

### Balance Considerations
- **Progressive power** - Higher mastery levels have longer cooldowns
- **Resource management** - Cooldowns prevent spell spamming
- **Specialization** - No single character can master all schools easily
- **Trade-offs** - Magical races may have other limitations

## File Structure

```
Defs/
├── TraitDefs/
│   ├── MorrowindMagicSchools.xml       # Core magic school mastery traits
│   └── ElderScrollsMagicAffinities.xml # Race-specific magic traits
├── AbilityDefs/
│   ├── MorrowindDestructionSpells.xml  # Fire, frost, shock spells
│   ├── MorrowindRestorationSpells.xml  # Healing and protection spells
│   ├── MorrowindIllusionSpells.xml     # Mind control and stealth spells
│   ├── MorrowindAlterationSpells.xml   # Transmutation and utility spells
│   ├── MorrowindConjurationSpells.xml  # Summoning and bound weapons
│   └── MorrowindMysticismSpells.xml    # Soul magic and teleportation
└── HediffDefs/
    └── MorrowindMagicEffects.xml       # Spell effect definitions
```

## Usage Guide

### For Players
1. **Choose magical races** for natural spell access
2. **Develop mastery** through trait progression
3. **Learn spell combinations** for tactical advantages
4. **Manage cooldowns** strategically in combat
5. **Specialize** in 1-2 schools for maximum effectiveness

### For Modders
- All definitions use standard RimWorld XML format
- Spell abilities can be extended or modified
- New schools can be added following the same pattern
- Race assignments can be customized
- Effect durations and cooldowns are easily adjustable

## Lore Accuracy

This system faithfully represents Morrowind's magic system:
- **Authentic schools** from The Elder Scrolls III
- **Lore-accurate spells** with familiar names and effects
- **Racial specializations** matching Elder Scrolls canon
- **Progressive mastery** reflecting magical education
- **Balanced implementation** suitable for RimWorld gameplay

The magic system adds significant depth to Elder Scrolls character roleplay while maintaining game balance and providing meaningful strategic choices.