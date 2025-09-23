# Thu'um System Documentation

This documentation covers the Thu'um (Dragon Shouts) system from The Elder Scrolls V: Skyrim, implemented for The Multiverse Mod.

## Overview

The Thu'um system introduces the ancient draconic art of Dragon Shouts, allowing characters to harness the power of the dragon language to perform incredible feats. This system is particularly suited for dragons but can be learned by other races through extensive training.

## Thu'um Mastery Trait

The Thu'um system is accessed through the **Thu'um Mastery** trait, which has four progressive degrees:

### Thu'um Apprentice (Degree 0)
- **Description**: A novice in the ancient art of the Thu'um
- **Abilities**: Basic understanding of dragon speech, limited shout power
- **Skill Bonuses**: +2 Intellectual, +1 Social
- **Benefits**: +0.1 Social Impact, -0.05 Mental Break Threshold

### Thu'um Adept (Degree 1)  
- **Description**: Experienced practitioner with multiple learned shouts
- **Abilities**: Greater power channeling, deeper dragon language understanding
- **Skill Bonuses**: +4 Intellectual, +2 Social, +1 Melee
- **Benefits**: +0.15 Social Impact, -0.1 Mental Break Threshold, +0.1 Psychic Sensitivity

### Thu'um Master (Degree 2)
- **Description**: Master whose voice carries the power of dragons
- **Abilities**: Devastating shout effectiveness, reality-reshaping words
- **Skill Bonuses**: +6 Intellectual, +4 Social, +2 Melee, +2 Shooting
- **Benefits**: +0.2 Social Impact, -0.15 Mental Break Threshold, +0.2 Psychic Sensitivity, +0.1 Global Learning

### Draconic Voice (Degree 3)
- **Description**: Near-dragon mastery of Thu'um with earth-shaking power
- **Abilities**: Supreme shout mastery approaching ancient dragon levels
- **Skill Bonuses**: +8 Intellectual, +6 Social, +3 Melee, +3 Shooting, +2 Medicine
- **Benefits**: +0.3 Social Impact, -0.2 Mental Break Threshold, +0.3 Psychic Sensitivity, +0.2 Global Learning, +0.1 Work Speed

## Available Thu'um Shouts

### Combat Shouts

#### Unrelenting Force (Fus Ro Dah)
- **Effect**: Powerful knockback attack that pushes enemies and breaks obstacles
- **Range**: 12 cells
- **Cooldown**: 1 hour
- **Damage**: 25 blunt damage + 8-cell knockback

#### Fire Breath (Yol Toor Shul)
- **Effect**: Breathe flame in a cone, burning enemies and igniting objects
- **Range**: 15 cells
- **Cooldown**: 1.33 hours
- **Damage**: 30 burn damage + 80% fire chance

#### Frost Breath (Fo Krah Diin)
- **Effect**: Exhale freezing cold that damages and slows enemies
- **Range**: 15 cells
- **Cooldown**: 1.33 hours
- **Damage**: 25 frostbite damage + slow effect

#### Soul Tear (Rii Vaaz Zol)
- **Effect**: Massive psychic damage that can instantly kill weak enemies
- **Range**: 30 cells
- **Cooldown**: 6.67 hours
- **Damage**: 80 psychic damage + instant kill <30% health

### Control Shouts

#### Ice Form (Iiz Slen Nus)
- **Effect**: Freeze target solid, immobilizing but reducing damage taken
- **Range**: 20 cells
- **Cooldown**: 1.67 hours
- **Duration**: 5 minutes

#### Marked for Death (Krii Lun Aus)
- **Effect**: Curse that weakens armor and health over time
- **Range**: 25 cells
- **Cooldown**: 2 hours
- **Duration**: 30 minutes

#### Dragonrend (Gol Hah Dov)
- **Effect**: Forces flying creatures to land and prevents flight
- **Range**: 40 cells
- **Cooldown**: 3.33 hours
- **Duration**: 10 minutes

#### Mortal Flesh (Joor Zah Frul)
- **Effect**: Strips magical defenses and protections
- **Range**: 25 cells
- **Cooldown**: 4.17 hours
- **Duration**: 15 minutes

### Enhancement Shouts

#### Become Ethereal (Feim Zii Gron)
- **Effect**: Become incorporeal and immune to damage
- **Range**: Self
- **Cooldown**: 3.33 hours
- **Duration**: 3 minutes

#### Dragon Aspect (Mul Qah Diiv)
- **Effect**: Take on draconic power with enhanced abilities
- **Range**: Self
- **Cooldown**: 16.67 hours
- **Duration**: 30 minutes

#### Elemental Fury (Su Grah Dun)
- **Effect**: Greatly increases attack and work speed
- **Range**: Self
- **Cooldown**: 2.5 hours
- **Duration**: 5 minutes

#### Slow Time (Tiid Klo Ul)
- **Effect**: Time slows around you, allowing supernatural speed
- **Range**: Self
- **Cooldown**: 5 hours
- **Duration**: 4 minutes

### Utility Shouts

#### Whirlwind Sprint (Wuld Nah Kest)
- **Effect**: Instantly teleport a short distance
- **Range**: 20 cells
- **Cooldown**: 30 minutes

#### Aura Whisper (Laas Yah Nir)
- **Effect**: Reveals all living beings in a large area
- **Range**: 40-cell radius
- **Cooldown**: 1 hour
- **Duration**: 10 minutes

#### Throw Voice (Zul Mey Gut)
- **Effect**: Creates a distraction at target location
- **Range**: 35 cells
- **Cooldown**: 30 minutes
- **Duration**: 5 minutes

#### Clear Skies (Lok Vah Koor)
- **Effect**: Changes weather to clear and removes contaminants
- **Range**: 50-cell radius
- **Cooldown**: 2.5 hours
- **Duration**: 1 hour

### Legendary Shouts

#### Storm Call (Strun Bah Qo)
- **Effect**: Summons a powerful thunderstorm with lightning strikes
- **Range**: 100-cell radius
- **Cooldown**: 8.33 hours
- **Duration**: 2 hours

#### Call of Valor (Hun Kaal Zoor)
- **Effect**: Summons heroic warrior spirits to fight alongside you
- **Range**: 15 cells
- **Cooldown**: 13.33 hours
- **Duration**: 30 minutes
- **Summons**: 3 Spectral Warriors

#### Curse Never Dying (Dur Neh Viir)
- **Effect**: Summons a spectral dragon ally
- **Range**: 20 cells
- **Cooldown**: 10 hours
- **Duration**: 1 hour
- **Summons**: 1 Spectral Dragon

## Integration with Dragon System

The Thu'um system integrates seamlessly with the existing Dragon race system:

- **Natural Progression**: Dragons naturally develop Thu'um mastery as they age
- **Trait Compatibility**: Thu'um Mastery stacks with Dragon Aging benefits
- **Lore Accuracy**: Higher dragon forms have increased Thu'um effectiveness
- **Balance Considerations**: Long cooldowns prevent spamming powerful effects

## Mechanical Features

### Prerequisites
- **Required Trait**: Thu'um Mastery (any degree)
- **Recommended Races**: Dragons (natural affinity), others through extensive training
- **Skill Synergies**: Benefits from high Intellectual and Social skills

### Cooldown System
- **Scaling Cooldowns**: More powerful shouts have longer cooldowns
- **Strategic Timing**: Players must choose when to use their most powerful abilities
- **Resource Management**: Limited uses encourage tactical decision-making

### Effect Durations
- **Temporary Effects**: Most shouts provide temporary benefits or debuffs
- **Stacking Prevention**: Multiple applications don't stack, but refresh duration
- **Natural Expiration**: Effects naturally fade over time

## Lore Accuracy

The Thu'um system faithfully represents the dragon shouts from The Elder Scrolls V: Skyrim:

- **Authentic Names**: All shouts use their canonical dragon language names
- **Accurate Effects**: Each shout's effect matches its in-game behavior
- **Power Scaling**: Effects scale appropriately with mastery level
- **Cultural Integration**: Fits naturally within The Elder Scrolls universe

## File Structure

```
Defs/
├── TraitDefs/
│   └── ThuumSystem.xml              # Thu'um Mastery trait progression
├── AbilityDefs/
│   ├── ThuumShouts.xml              # Core combat and utility shouts
│   ├── ThuumShouts2.xml             # Advanced and legendary shouts
│   └── ThuumShouts3.xml             # Elite and summoning shouts
└── HediffDefs/
    └── ThuumEffects.xml             # Status effects and conditions
```

## Integration Notes

- **XML Compatibility**: All definitions use standard RimWorld XML format
- **Trait Requirements**: All shouts require Thu'um Mastery trait
- **Balanced Progression**: Power scales with trait degree and cooldown length
- **Cross-System Integration**: Works seamlessly with existing dragon and faction systems

## Gameplay Impact

The Thu'um system adds:

1. **Strategic Depth**: Powerful abilities with meaningful cooldowns
2. **Character Specialization**: Unique progression path for dragon speakers
3. **Combat Variety**: Multiple tactical options in different situations
4. **Lore Immersion**: Authentic Elder Scrolls experience in RimWorld
5. **Endgame Content**: Legendary shouts provide long-term goals

This system significantly enhances the fantasy elements of The Multiverse Mod while maintaining balance and providing meaningful choices for players interested in draconic magic and Thu'um mastery.