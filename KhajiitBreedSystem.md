# Khajiit Breed System Documentation

This documentation covers the comprehensive Khajiit breed system implementation for The Multiverse Mod, featuring lore-accurate breed variations, moon cycle influences, and cultural/religious systems.

## Overview

The Khajiit Breed System implements the canon Elder Scrolls lore regarding the 17 different Khajiit breeds determined by the phases of Masser and Secunda (Jone and Jode) at birth. This system adds:

- **12 distinct Khajiit breeds** as separate playable races
- **Breed-specific traits** with unique abilities and stat bonuses
- **Cultural traits** for Anequinan and Pellitine regions
- **Religious memes** for traditional Khajiit faiths
- **Moon cycle system** affecting Khajiit abilities
- **Lore-accurate characteristics** for each breed

## Implemented Khajiit Breeds

### Humanoid Breeds
1. **Ohmes** - Most human-like, excellent diplomats and spies
2. **Ohmes-raht** - Larger Ohmes, skilled merchants and craftsmen
3. **Suthay** - Agile with obvious feline features, common in other provinces
4. **Suthay-raht** - Larger Suthay, excellent warriors and hunters

### Quadrupedal Breeds
5. **Alfiq** - House cat size, powerful spellcasters
6. **Alfiq-raht** - Lynx size, mysterious magical advisors
7. **Dagi** - Small tree-dwellers, natural climbers and scouts
8. **Dagi-raht** - Jaguar size, forest hunters with stealth mastery

### Large Breeds
9. **Cathay** - Most common in Elsweyr, balanced warriors and laborers
10. **Cathay-raht** - Largest common breed, powerful fighters and workers

### Giant Breeds
11. **Senche** - Intelligent, can speak, natural mounts
12. **Pahmar** - Tiger-like, cannot speak, beasts of burden

### Mythical Breed
13. **Mane** - Rarest breed, spiritual/political leader (eclipse birth)

## Cultural Systems

### Regional Cultures

#### Anequinan (Northern Elsweyr)
- **Desert Heritage**: Enhanced survival in harsh conditions
- **Warrior Traditions**: Emphasis on combat and tribal honor
- **Nomadic Lifestyle**: Movement and stealth bonuses

#### Pellitine (Southern Elsweyr)
- **River Heritage**: Agricultural and crafting expertise
- **Merchant Traditions**: Trade and diplomatic bonuses
- **Settled Communities**: Construction and social bonuses

### Additional Cultural Traits
- **Lunar Awareness**: Connection to moon cycles
- **Moon-sugar Refinement**: Resistance to addiction
- **Caravan Heritage**: Travel and trade bonuses
- **Confederacy Loyalty**: Unity among all breeds

## Religious Systems

### Traditional Moon Worship
- **Deities**: Jone (Masser) and Jode (Secunda)
- **Focus**: Lunar cycles, moon-sugar sanctity, breed acceptance
- **Precepts**: Honor moons, respect sacred substances, welcome all breeds
- **Impact**: Medium (2)

### Riddle'Thar Epiphany
- **Deities**: Riddle'Thar, Azurah, moral teachers
- **Focus**: Reformed religion with practical ethics
- **Precepts**: Honest trade, family loyalty, elder wisdom
- **Impact**: Medium (2)

### Azurah's Children
- **Deities**: Azurah, primal feline spirits
- **Focus**: Ancient faith recognizing Azurah as divine mother
- **Precepts**: Feline reverence, ancient ways preservation
- **Impact**: Low (1)

## Moon Cycle System

### Moon Phase Effects
Khajiit are affected by current lunar phases through hediffs:

- **New Moon**: Enhanced stealth and intellect, reduced physical power
- **Waxing Moon**: Increased magical aptitude and social skills
- **Full Moon**: Greatly enhanced physical prowess and combat ability
- **Waning Moon**: Enhanced wisdom and healing, reduced aggression

### Special Lunar Events
- **Lunar Eclipse**: Rare blessing marking potential Mane candidates
- **Moon-sugar Blessing**: Enhanced abilities from sacred substance

## Breed Characteristics

### Stat Variations by Breed
- **Body Size**: 0.3 (Alfiq) to 2.0 (Senche)
- **Movement Speed**: 3.8 (Senche) to 6.2 (Dagi)
- **Lifespan**: 90 (standard) to 200 (Mane)
- **Market Value**: 3100 to 8000 (Mane)

### Unique Abilities by Category
- **Humanoid**: Diplomacy, trade, agility, combat
- **Quadrupedal**: Magic, stealth, climbing, scouting
- **Large**: Strength, endurance, balanced abilities
- **Giant**: Wisdom, loyalty, primal strength
- **Mythical**: Divine leadership, spiritual authority

## File Structure

```
Defs/
├── RaceDefs/
│   ├── BeastRaces.xml           # Updated original Khajiit (mixed breed)
│   └── KhajiitBreeds.xml        # 12 distinct breed definitions
├── TraitDefs/
│   ├── KhajiitBreedTraits.xml   # Breed-specific traits
│   └── KhajiitCulturalTraits.xml # Cultural and regional traits
├── MemeDefs/
│   └── KhajiitReligiousMemes.xml # Three religious memes
├── RulePackDefs/
│   └── KhajiitDeityNames.xml    # Deity name generators
├── PreceptDefs/
│   └── KhajiitReligiousPrecepts.xml # Religious precepts
├── ThoughtDefs/
│   └── KhajiitReligiousThoughts.xml # Mood effects for religious compliance
└── HediffDefs/
    └── KhajiitMoonCycle.xml     # Moon phase effects and blessings
```

## Integration with Existing Systems

The Khajiit breed system integrates seamlessly with existing mod components:
- Compatible with existing Elder Scrolls racial traits
- Works alongside faction and ideologion systems
- Maintains balance with other beast races
- Preserves backward compatibility with original Khajiit race

## Lore Accuracy

This system faithfully represents Elder Scrolls lore:
- **Accurate breed descriptions** based on canon sources
- **Proper moon phase associations** for each breed
- **Authentic cultural divisions** (Anequina vs Pellitine)
- **Canon religious systems** with proper deities and beliefs
- **Appropriate stat distributions** reflecting lore characteristics

## Gameplay Impact

### Balance Considerations
- Each breed has distinct advantages and disadvantages
- No single breed is universally superior
- Larger breeds trade mobility for strength
- Smaller breeds trade durability for specialized abilities

### Roleplay Opportunities
- Create authentic Elsweyr communities with mixed breeds
- Establish traditional moon-worshipping colonies
- Build merchant caravans with trade-focused breeds
- Form warrior clans with combat-oriented breeds

### Faction Integration
- Religious memes provide ideological frameworks
- Cultural traits support regional specializations
- Moon cycle effects add dynamic gameplay elements
- Breed diversity encourages varied colony compositions

## Usage

Players can:
1. **Select specific breeds** during pawn creation or recruitment
2. **Apply cultural traits** to represent regional origins
3. **Assign religious ideologies** to create thematic communities
4. **Experience moon cycle effects** as dynamic gameplay elements
5. **Create diverse colonies** with multiple breeds working together

Each breed provides unique gameplay experiences while maintaining fidelity to Elder Scrolls lore and established RimWorld mechanics.