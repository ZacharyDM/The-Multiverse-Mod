# Ashlander Expansion Documentation

This documentation covers the expanded Ashlander clan system, featuring universal ranks and unique clan-specific traits for the eight major Ashlander tribes of Morrowind.

## Overview

The Ashlander expansion introduces a comprehensive rank system shared across all Ashlander clans, plus unique traits for each of the eight major clans that reflect their individual characteristics and specializations.

### Universal Ashlander Ranks

All Ashlander clans share the same rank progression system based on the traditional hierarchy from Morrowind:

**Rank Progression (0-9):**
- **0. Clanfriend** - An outsider who has earned respect
- **1. Hearthfriend** - Welcomed into the extended family  
- **2. Brother/Sister** - Bound by sacred oaths and shared trials
- **3. Initiate** - Beginning to understand Ashlander ways
- **4. Clanholder** - Holds property and standing in the clan
- **5. Guide** - Leads others through trials of clan life
- **6. Champion** - Represents clan strength and honor
- **7. Gulakhan** - War-leader, second only to the Ashkhan
- **8. Farseer** - Visionary prophet who communes with ancestors
- **9. Ashkhan** - Paramount chief and spiritual guide

### Clan-Specific Traits

Each of the eight Ashlander clans has unique traits that reflect their distinctive characteristics:

## Ahemmusa Clan
- **Focus**: Peaceful wisdom, endurance, healing
- **Skills**: Medicine, Intellectual, Social, Artistic
- **Bonuses**: Learning speed, pain resistance, immunity, medical quality
- **Progression**: Ahemmusa Clanmate → Ahemmusa Elder

## Urshilaku Clan  
- **Focus**: Traditional keepers of prophecy and heritage
- **Skills**: Intellectual, Social, Melee, Artistic
- **Bonuses**: Mental stability, social influence, negotiation, trade
- **Progression**: Urshilaku Clanmate → Urshilaku Wise Woman

## Erabenimsun Clan
- **Focus**: Fierce warriors bred for battle
- **Skills**: Melee, Shooting, Animals
- **Bonuses**: Combat effectiveness, heat resistance, movement speed
- **Progression**: Erabenimsun Warrior → Erabenimsun Champion

## Zainab Clan
- **Focus**: Resourceful traders and diplomats  
- **Skills**: Social, Intellectual, Crafting, Artistic
- **Bonuses**: Trade prices, negotiation, work speed, social impact
- **Progression**: Zainab Trader → Zainab Merchant Prince

## Kagesh Clan
- **Focus**: Mysterious rituals and arcane secrets
- **Skills**: Intellectual, Artistic, Medicine, Social  
- **Bonuses**: Research speed, mental resistance, psychic sensitivity
- **Progression**: Kagesh Mystic → Kagesh Ritualist

## Ulath Clan
- **Focus**: Secretive survival and stealth mastery
- **Skills**: Shooting, Animals, Plants, Melee
- **Bonuses**: Movement speed, accuracy, carrying capacity, foraging
- **Progression**: Ulath Stalker → Ulath Shadow Walker

## Vereansu Clan
- **Focus**: Deep spiritual connection to ancestors
- **Skills**: Social, Intellectual, Artistic, Medicine
- **Bonuses**: Psychic sensitivity, mental stability, social impact, learning
- **Progression**: Vereansu Spirit-Touched → Vereansu Spirit Speaker

## Mabrigash Clan
- **Focus**: Matriarchal mystical warrior society
- **Skills**: Melee, Medicine, Artistic, Social
- **Bonuses**: Medical quality, psychic sensitivity, combat effectiveness
- **Progression**: Mabrigash Sister → Mabrigash Matriarch
- **Note**: Traditionally female-only clan in lore

## Rank System Requirements

Based on the original Morrowind progression requirements:

| Rank | Required Attributes | Required Skills |
|------|-------------------|----------------|
| 0. Clanfriend | Agility 30, Endurance 30 | — |
| 1. Hearthfriend | Agility 40, Endurance 30 | One skill at 30, two at 20 |
| 2. Brother/Sister | Agility 45, Endurance 35 | One skill at 40, two at 20 |
| 3. Initiate | Agility 50, Endurance 40 | One skill at 50, two at 25 |
| 4. Clanholder | Agility 55, Endurance 45 | One skill at 60, two at 25 |
| 5. Guide | Agility 60, Endurance 50 | One skill at 70, two at 30 |
| 6. Champion | Agility 65, Endurance 55 | One skill at 80, two at 30 |
| 7. Gulakhan | Agility 70, Endurance 60 | One skill at 90, two at 35 |
| 8. Farseer | Agility 75, Endurance 65 | One skill at 100, two at 35 |
| 9. Ashkhan | Agility 80, Endurance 70 | One skill at 110, two at 35 |

*Note: In RimWorld implementation, these requirements would need to be adapted to the game's skill and trait system.*

## Integration Notes

- All definitions use standard RimWorld XML format
- Traits provide skill bonuses using the same system as the base game
- Stat offsets are balanced to provide meaningful progression without breaking gameplay
- Multiple trait degrees allow for character development over time
- Each clan has unique bonuses that reflect their lore-accurate specializations

## File Structure

```
Defs/
├── TraitDefs/
│   └── AshlanderClans.xml          # 8 clan-specific traits with progression
└── RankDefs/RankDefs_Dunmer/RankDefs_Ashlanders/
    └── RankDefs_Ashlanders.xml     # Universal Ashlander rank system
```

This structure allows for easy expansion and modification while maintaining clear separation between the universal rank system and clan-specific traits.

## Lore Accuracy

The system faithfully represents the Ashlander clans from The Elder Scrolls III: Morrowind:
- Rank progression matches the original game exactly
- Each clan's traits reflect their established lore characteristics
- Skill bonuses align with each clan's traditional focus areas
- Descriptions maintain the tone and terminology of Morrowind

## Quest Integration Potential

The system is designed to be quest-linked and unlockable:
- Traits can be gained through specific questlines involving each clan
- Rank progression could be tied to accomplishments and story events  
- Reflects the player's journey through Ashlander society and acceptance