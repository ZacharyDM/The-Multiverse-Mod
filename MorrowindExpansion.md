# Morrowind Expansion Documentation

This documentation covers the comprehensive addition of diseases, animals, and plants from The Elder Scrolls III: Morrowind to The Multiverse Mod.

## Overview

The Morrowind expansion introduces authentic content from the iconic Elder Scrolls game, including:

### Diseases (16 total)
- **Corpus** (existing) - Divine disease from House Dagoth
- **15 new diseases** covering all major ailments from Morrowind

### Animals (11 species)
- **Native creatures** from Morrowind's diverse ecosystems
- **Domesticated animals** used by Dunmer civilization
- **Dangerous predators** that roam the ashlands

### Plants (9 species)
- **Agricultural crops** that form the basis of Dunmer farming
- **Decorative flowers** for beautification and alchemy
- **Medicinal herbs** with healing properties

## Diseases

### Common Diseases
| Disease | Primary Effects | Severity Stages | Transmission |
|---------|----------------|-----------------|--------------|
| **Ataxia** | Coordination/dexterity loss | Mild → Moderate → Severe | Damp underground areas |
| **Bone Break Fever** | Physical weakness, muscle aches | Mild → Moderate → Severe | Infected animal bites |
| **Collywobbles** | Stomach cramps, nausea | Mild → Moderate → Severe | Tainted food/water |
| **Rockjoint** | Joint stiffness, reduced mobility | Mild → Moderate → Severe | Damp climates |
| **Yellow Tick** | Skin yellowing, social impact | Mild → Moderate → Severe | Tick-borne |

### Severe Diseases
| Disease | Primary Effects | Special Properties |
|---------|----------------|-------------------|
| **Chanthrax Blight** | Mental/social impairment | Magical blight |
| **Helljoint** | Extreme joint pain | Severe rockjoint variant |
| **Serpiginous Dementia** | Progressive mental decline | Cognitive impairment |
| **Wither** | Multi-system failure | Life-threatening |
| **Brown Rot** | Flesh necrosis | Socially isolating |

### Disease Mechanics
- **Progressive stages** with increasing severity
- **Immunization system** allows recovery with proper care
- **Balanced stat effects** that don't break gameplay
- **Lore-accurate symptoms** matching Morrowind descriptions

## Animals

### Domesticated Species

#### Guar
- **Role**: Primary pack animal and mount
- **Traits**: Docile, hardy, trainable
- **Market Value**: 400 gold
- **Special**: Advanced trainability, pack animal capability

#### Kwama Worker
- **Role**: Underground hive worker
- **Traits**: Docile, communal, hardworking
- **Market Value**: 200 gold
- **Special**: Pack animal, armored shell

### Predatory Species

#### Alit
- **Role**: Apex predator of ashlands
- **Traits**: Large, aggressive, jumping ability
- **Market Value**: 600 gold
- **Combat**: Bite, claws, tail whip attacks

#### Kagouti
- **Role**: Territorial tusked predator
- **Traits**: Fierce, territorial, tusked
- **Market Value**: 350 gold
- **Combat**: Powerful tusk stabs, head bash

#### Kwama Warrior
- **Role**: Hive defender
- **Traits**: Armored, aggressive, protective
- **Market Value**: 450 gold
- **Combat**: Strong mandibles, armored shell

### Unique Species

#### Bull Netch
- **Role**: Massive floating creature
- **Traits**: Gas-filled, electrical attacks
- **Market Value**: 800 gold
- **Special**: Flying, electrical tentacles

#### Cliff Racer
- **Role**: Notorious flying pest
- **Traits**: Persistent, aerial, aggressive
- **Market Value**: 120 gold
- **Special**: Flying, swooping attacks

#### Nix-Hound
- **Role**: Pack hunter
- **Traits**: Beak-like mouth, pack behavior
- **Market Value**: 250 gold
- **Combat**: Piercing beak attacks

## Plants

### Food Crops

#### Saltrice
- **Role**: Staple grain crop of Dunmer
- **Growing**: 9 days, requires good soil (0.7 fertility)
- **Yield**: 18 units, nutritious and long-lasting
- **Market Value**: 1.2 gold per unit

#### Wickwheat
- **Role**: Premium grain crop
- **Growing**: 10 days, requires excellent soil (0.8 fertility)
- **Yield**: 22 units, superior quality
- **Market Value**: 1.4 gold per unit

#### Ash Yam
- **Role**: Hardy volcanic tuber
- **Growing**: 12 days, thrives in poor soil (0.3 fertility)
- **Yield**: 25 units, highly nutritious
- **Market Value**: 1.6 gold per unit
- **Special**: Grows in volcanic ash, most resilient crop

#### Marshmerrow
- **Role**: Wetland staple food
- **Growing**: 7 days, grows in water/marsh (0.5 fertility)
- **Yield**: 12 units, mild restorative properties
- **Market Value**: 1.0 gold per unit

### Decorative & Alchemical Plants

#### Gold Kanet
- **Role**: Beautiful ornamental flower
- **Beauty**: +20 per plant
- **Growing**: 8 days, decorative purpose
- **Yield**: 6 flowers, alchemical value
- **Market Value**: 3.5 gold per flower

#### Fire Petal
- **Role**: Heat-resistant volcanic flower
- **Beauty**: +15 per plant
- **Growing**: 6 days, low soil requirements
- **Yield**: 4 flowers, fire resistance properties
- **Market Value**: 4.0 gold per flower

#### Hackle-Lo Leaf
- **Role**: Primary medicinal plant
- **Growing**: 9 days, requires good soil
- **Yield**: 8 leaves, healing properties
- **Market Value**: 6.0 gold per leaf
- **Special**: Medical applications, slow deterioration

#### Comberry
- **Role**: Energizing alchemical fruit
- **Beauty**: +12 per plant
- **Growing**: 7 days, moderate soil needs
- **Yield**: 10 berries, mental enhancement
- **Market Value**: 2.0 gold per berry

## File Structure

```
Defs/
├── HediffDefs/
│   ├── CorpusDisease.xml           # Existing House Dagoth disease
│   ├── MorrowindDiseases.xml       # Ataxia, Bone Break Fever, etc.
│   ├── MorrowindDiseases2.xml      # Droops, Greenspore, etc.
│   └── MorrowindDiseases3.xml      # Swamp Fever, Wither, etc.
├── ThingDefs/Races/
│   ├── MorrowindAnimals.xml        # Guar, Kagouti, Alit
│   ├── MorrowindAnimals2.xml       # Nix-Hound, Shalk, etc.
│   └── MorrowindAnimals3.xml       # Netch, Kwama species
├── PawnKindDefs/
│   ├── PawnKind_MorrowindAnimals.xml
│   └── PawnKind_MorrowindAnimals2.xml
└── ThingDefs/Plants/
    ├── MorrowindCrops.xml          # Food crops and products
    └── MorrowindPlants.xml         # Decorative and alchemical plants
```

## Integration Notes

### Compatibility
- All definitions use standard RimWorld XML format
- Compatible with existing faction systems
- Balanced for vanilla gameplay experience
- No conflicts with base game mechanics

### Balance Considerations
- **Diseases**: Progressive but not game-breaking
- **Animals**: Varied roles from pets to pack animals to threats
- **Plants**: Diverse growing requirements and uses
- **Market values**: Scaled appropriately for game economy

### Texture Requirements
The mod expects texture files at the following paths (textures not included in code):
- `Things/Pawn/Animal/[AnimalName]/[AnimalName].png`
- `Things/Plant/[PlantName].png`
- `Things/Item/Resource/[ResourceName].png`

## Lore Accuracy

This expansion faithfully represents content from The Elder Scrolls III: Morrowind:

### Diseases
- **Authentic symptoms** matching original game effects
- **Lore-appropriate transmission** methods and descriptions
- **Cultural context** reflecting Morrowind's harsh environment

### Animals
- **Accurate behaviors** and ecological roles
- **Proper relationships** between predators and prey
- **Cultural significance** to Dunmer society

### Plants
- **Agricultural realism** reflecting Dunmer farming practices
- **Alchemical properties** true to Elder Scrolls tradition
- **Environmental adaptation** to volcanic and marsh biomes

## Quest Integration Potential

The content is designed for future quest integration:
- **Disease outbreaks** and cure-seeking storylines
- **Animal taming** and breeding questlines
- **Agricultural expansion** and crop development
- **Alchemical research** using native plants
- **Ecological balance** management scenarios

This comprehensive expansion significantly enhances the Elder Scrolls experience within RimWorld, providing authentic content that respects both franchises while creating engaging gameplay opportunities.