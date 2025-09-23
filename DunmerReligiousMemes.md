# Dunmer Religious Memes Documentation

This documentation covers the ideologion memes system for the various Dunmer religious factions in The Multiverse Mod.

## Overview

The Dunmer Religious Memes system adds four distinct ideological frameworks representing the major religious traditions of Morrowind from The Elder Scrolls III. Each meme provides unique deities, beliefs, precepts, and social structures that align with the established lore.

## Religious Memes

### 1. Tribunal Worship (Impact: 2)
- **Deities**: Almalexia, Sotha Sil, Vivec (Living Gods)
- **Focus**: Veneration of the three god-kings who achieved divinity through wisdom, struggle, and sacrifice
- **Associated Factions**: Tribunal Temple, House Indoril
- **Worship Room**: Temple Hall
- **Key Precepts**: Temple Faith - Following Temple orthodoxy and venerating the Living Gods

### 2. The Sixth House (Impact: 3)
- **Deities**: Dagoth Ur (The Sharmat)
- **Focus**: Divine disease worship and transformation through Corpus
- **Associated Factions**: House Dagoth
- **Worship Room**: Corpus Chamber
- **Key Precepts**: Corpus Blessing - Embracing Corpus as divine gift rather than curse

### 3. The Reclaimations (Impact: 1)
- **Deities**: Azura, Boethiah, Mephala (Good Daedra) + Ancestral Spirits
- **Focus**: Traditional Ashlander faith with ancestor veneration and Daedric worship
- **Associated Factions**: All Ashlander Clans
- **Worship Room**: Ancestor Shrine
- **Key Precepts**: Ancestor Wisdom - Honoring ancestors and preserving ancient traditions

### 4. The Tribunal (Impact: 1)
- **Deities**: Living Gods (Tribunal) + Noble Ancestors, House Founders
- **Focus**: Main Great House religion combining Tribunal worship with bloodline veneration
- **Associated Factions**: All Great Houses (excluding House Dagoth)
- **Worship Room**: Ancestral Hall
- **Key Precepts**: House Honor - Upholding House dignity and noble traditions

## Mechanical Features

### Deity Systems
Each meme includes appropriate deity name generators with lore-accurate names and titles:
- **Tribunal**: Living Gods titles and epithets
- **The Sixth House**: Dagoth Ur variants and Corpus-related titles
- **The Reclaimations**: Good Daedra names and ancestral spirits
- **The Tribunal (Great House)**: Living Gods and noble ancestors

### Thought Effects
Religious adherents experience mood effects based on following or violating their beliefs:
- **Positive thoughts**: +6 to +10 mood for 4-5 days when fulfilling religious duties
- **Negative thoughts**: -10 to -15 mood for 6-8 days when violating religious precepts

### Social Integration
- **Symbol packs** provide thematically appropriate ideology names and terminology
- **Ritual patterns** define appropriate religious roles and duties
- **Worship rooms** create dedicated religious spaces

## Lore Accuracy

The religious memes faithfully represent the major faith systems from Morrowind:

### Tribunal Temple
- Accurately represents the state religion of Morrowind during the Third Era
- Includes the three Living Gods with their canonical roles and domains
- Reflects the Temple's orthodoxy and structured hierarchy

### The Sixth House
- Captures the twisted spirituality of House Dagoth
- Represents Corpus as divine transformation rather than mere disease
- Maintains the cultish devotion to Dagoth Ur as god-king

### The Reclaimations
- Honors the original Chimer religion focusing on worship of the 4 good Daedra
- Includes the Good Daedra who became the "Anticipations" of the Tribunal
- Preserves the ancestor veneration central to nomadic culture
- Recognizes the other bad Daedra as being of the House of Troubles

### The Tribunal (Great Houses)
- Represents the canonical main religion that all Great Houses follow
- Combines Living Gods worship with formal, hierarchical practices
- Emphasizes bloodline, honor, and House prestige alongside Tribunal veneration
- Connects to the political and social structures of Great House society

## File Structure

```
Defs/
├── MemeDefs/
│   └── DunmerReligiousMemes.xml     # Four main religious memes
├── RulePackDefs/
│   └── DunmerDeityNames.xml         # Deity name generators
├── PreceptDefs/
│   └── DunmerReligiousPrecepts.xml  # Religious precepts and requirements
└── ThoughtDefs/
    └── DunmerReligiousThoughts.xml  # Mood effects for religious compliance

Languages/English/Keyed/
└── TheMultiverseMod.xml             # Localization strings
```

## Integration with Existing Systems

The religious memes integrate seamlessly with existing faction and trait systems:
- Compatible with Tribunal Temple Orders and ranks
- Works alongside The Sixth House Corpus traits
- Complements The Reclaimations clan specializations
- Enhances Great House political structures through The Tribunal

## Usage

Players can assign these ideologies to their colonies to create authentic Morrowind religious communities:
1. **Tribunal Temple Colony**: Formal religious hierarchy with temple structures
2. **The Sixth House Outpost**: Corpus-worshipping cult settlement
3. **The Reclaimations Camp**: Traditional nomadic religious practices
4. **Great House Manor**: Tribunal worship combined with noble bloodline veneration

Each ideology provides unique gameplay experiences while maintaining fidelity to Elder Scrolls lore and established RimWorld mechanics.