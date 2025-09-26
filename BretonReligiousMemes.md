# Breton Religious Memes Documentation

This documentation covers the ideological memes system for the various Breton religious factions in The Multiverse Mod.

## Overview

The Breton Religious Memes system adds three distinct ideological frameworks representing the major religious traditions of High Rock from The Elder Scrolls universe. Each meme provides unique deities, beliefs, precepts, and social structures that align with the diverse spiritual landscape of the Bretons.

## Religious Memes

### 1. Eight Divines Worship (Impact: 2)
- **Deities**: Akatosh, Arkay, Dibella, Julianos, Kynareth, Mara, Stendarr, Zenithar
- **Focus**: Imperial divine faith emphasizing law, order, and righteous conduct
- **Associated Factions**: All Imperial-aligned Breton kingdoms
- **Worship Room**: Divine Chapel
- **Key Precepts**: Divine Obedience - Following righteous path through moral conduct

### 2. Daedric Scholarship (Impact: 3)
- **Deities**: Hermaeus Mora (primary), Azura, Nocturnal
- **Focus**: Pursuit of forbidden knowledge and magical research
- **Associated Factions**: Mages Guild, secretive scholarly cults
- **Worship Room**: Forbidden Library
- **Key Precepts**: Scholarly Curiosity - Embracing pursuit of all knowledge

### 3. Ancestral Spirits (Impact: 1)
- **Deities**: Ancestral Spirits and ancient Breton nobility
- **Focus**: Traditional pre-Imperial faith with ancestor veneration
- **Associated Factions**: Traditional Highland clans, old Breton houses
- **Worship Room**: Ancestral Shrine
- **Key Precepts**: Ancestral Reverence - Honoring wisdom and traditions of forebears

## Mechanical Features

### Deity Systems
Each meme includes appropriate deity name generators with lore-accurate names and titles:
- **Eight Divines**: Traditional Imperial divine titles and epithets
- **Daedric Scholarship**: Hermaeus Mora variants and knowledge-focused Daedric titles
- **Ancestral Spirits**: Ancient Breton noble names and ancestral spirit titles

### Thought Effects
Religious adherents experience mood effects based on following or violating their beliefs:
- **Positive thoughts**: +6 to +10 mood for 4-6 days when fulfilling religious duties
- **Negative thoughts**: -8 to -15 mood for 5-8 days when violating religious precepts

### Social Integration
- **Symbol packs** provide thematically appropriate ideology names and terminology
- **Ritual patterns** define appropriate religious roles and duties
- **Worship rooms** create dedicated religious spaces

## Lore Accuracy

This system faithfully represents Elder Scrolls lore:
- **Eight Divines**: Canonical Imperial pantheon widely adopted in High Rock
- **Daedric Cults**: Hermaeus Mora worship fitting for scholarly Breton culture
- **Ancestral Spirits**: Pre-Imperial Breton traditions and ancient bloodline veneration
- **Appropriate cultural integration** with existing Breton kingdom traits
- **Authentic naming conventions** and religious terminology

## File Structure

```
Defs/
├── MemeDefs/
│   └── BretonReligiousMemes.xml     # Three main religious memes
├── RulePackDefs/
│   └── BretonDeityNames.xml         # Deity name generators
├── PreceptDefs/
│   └── BretonReligiousPrecepts.xml  # Religious precepts and requirements
└── ThoughtDefs/
    └── BretonReligiousThoughts.xml  # Mood effects for religious compliance

Languages/English/Keyed/
└── TheMultiverseMod.xml             # Localization strings
```

## Integration with Existing Systems

The religious memes integrate seamlessly with existing faction and trait systems:
- Compatible with Breton cultural traits (kingdoms and unique groups)
- Works alongside Imperial Legion traditions for Eight Divines worship
- Complements magical institutions for Daedric Scholarship
- Supports traditional highland cultures for Ancestral Spirits worship
- Maintains balance with other religious systems in the mod

## Usage

Players can assign these ideologies to their colonies to create authentic High Rock religious communities:
1. **Divine Chapel Colony**: Imperial-aligned religious settlement following the Eight Divines
2. **Scholarly Cult Settlement**: Knowledge-seeking community devoted to forbidden research
3. **Ancestral Shrine Community**: Traditional Breton settlement honoring ancient ways

Each ideology provides unique gameplay experiences while maintaining fidelity to Elder Scrolls lore and established RimWorld mechanics.