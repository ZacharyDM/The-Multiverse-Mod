# Khajiit Regional Styles Documentation

This documentation covers the Khajiit regional style system that provides unique apparel, weapons, and building styles for the two major regions of Elsweyr, plus specialized apparel for non-bipedal Khajiit breeds.

## Overview

The Khajiit Regional Styles system implements the cultural differences between northern and southern Elsweyr:

- **Anequinan Style** - Desert warrior culture of northern Elsweyr
- **Pellitine Style** - Merchant river culture of southern Elsweyr  
- **Quadrupedal Apparel** - Specialized equipment for non-bipedal Khajiit breeds

## Regional Styles

### Anequinan (Northern Elsweyr)

The harsh badlands and deserts of northern Elsweyr have shaped a warrior culture focused on survival and martial prowess.

**Cultural Characteristics:**
- Nomadic desert tribes
- Warrior traditions emphasizing honor and strength
- Survival skills adapted to harsh climates
- Earth-toned, practical designs

**Style Features:**
- Desert camouflage colors (browns, tans, sandy hues)
- Practical, weathered designs
- Tribal motifs and warrior symbols
- Emphasis on mobility and stealth

### Pellitine (Southern Elsweyr)  

The fertile river valleys and prosperous cities of southern Elsweyr have fostered a sophisticated merchant culture.

**Cultural Characteristics:**
- Settled agricultural communities
- Merchant and diplomatic traditions
- Craftsmanship and artistic refinement
- Rich colors displaying wealth and status

**Style Features:**
- Rich, vibrant colors (deep blues, purples, golds)
- Elegant patterns and sophisticated designs
- High-quality materials and craftsmanship
- Emphasis on social influence and trade bonuses

## Apparel Items

### Regional Apparel

#### Anequinan Desert Garb
- **Type**: Basic clothing
- **Features**: Desert survival bonuses, stealth enhancement
- **Materials**: Fabric, leather
- **Bonuses**: +Movement speed, +Hunting stealth, +Heat resistance

#### Anequinan Warrior Armor  
- **Type**: Medium armor
- **Features**: Combat-focused protection with mobility
- **Materials**: Leather, metal studs
- **Bonuses**: +Movement speed, +Hunting stealth, +Melee hit chance

#### Pellitine Merchant Robes
- **Type**: Elegant clothing
- **Features**: Social and trade bonuses
- **Materials**: Fine fabrics
- **Bonuses**: +Social impact, +Trade price improvement, +Negotiation ability

#### Pellitine Diplomatic Vest
- **Type**: Light armor
- **Features**: Protection with diplomatic benefits
- **Materials**: Fabric, precious metals
- **Bonuses**: +Social impact, +Trade price improvement, +Negotiation ability

### Quadrupedal Apparel

Special apparel designed for non-bipedal Khajiit breeds that cannot wear standard humanoid armor.

#### Alfiq Magical Collar
- **Breeds**: Alfiq, Alfiq-raht
- **Type**: Magical enhancement
- **Features**: Psychic amplification for spellcasting
- **Bonuses**: +Psychic sensitivity, +Psychic entropy recovery

#### Dagi Scout Harness
- **Breeds**: Dagi, Dagi-raht  
- **Type**: Utility harness
- **Features**: Climbing aids and stealth enhancement
- **Bonuses**: +Movement speed, +Hunting stealth, +Carrying capacity

#### Senche War Barding
- **Breeds**: Senche
- **Type**: Heavy armor
- **Features**: Full protection for mount-warriors
- **Bonuses**: +Melee damage, +Carrying capacity, -Movement speed

#### Pahmar Beast Armor
- **Breeds**: Pahmar
- **Type**: Beast armor  
- **Features**: Protection for tiger-like warriors
- **Bonuses**: +Melee damage, +Carrying capacity, -Movement speed

#### Universal Quadrupedal Cloak
- **Breeds**: All quadrupedal Khajiit
- **Type**: Weather protection
- **Features**: Climate protection for all non-bipedal breeds
- **Bonuses**: +Cold/Heat insulation

## File Structure

```
Defs/StyleCategoryDefs/
├── KhajiitStyles.xml                # Regional style categories
├── KhajiitApparelStyles.xml         # Apparel style definitions  
├── KhajiitWeaponStyles.xml          # Weapon style definitions
└── KhajiitBuildingStyles.xml        # Building style definitions

Defs/ThingDefs/Apparel/Khajiit/
├── KhajiitRegionalApparel.xml       # Anequinan and Pellitine apparel
└── KhajiitQuadrupedalApparel.xml    # Non-bipedal specialized apparel

Textures/Things/Pawn/Humanlike/Apparel/Khajiit/
├── Anequinan/                       # Desert warrior textures
├── Pellitine/                       # Merchant culture textures
└── Quadrupedal/                     # Non-bipedal apparel textures

Textures/Item/Equipment/WeaponMelee/Khajiit/
├── Anequinan/                       # Desert weapon textures
└── Pellitine/                       # Merchant weapon textures

Textures/Building/*/Khajiit/
├── Anequinan/                       # Desert architecture textures  
└── Pellitine/                       # River city architecture textures
```

## Integration with Khajiit Breed System

The regional styles integrate seamlessly with the existing Khajiit breed system:

- **Cultural Traits**: Anequinan and Pellitine traits from `KhajiitCulturalTraits.xml` provide mechanical backing for the regional differences
- **Breed Restrictions**: Quadrupedal apparel uses `allowedRaces` to restrict items to appropriate breeds
- **Lore Consistency**: All items maintain consistency with Elder Scrolls lore regarding Khajiit culture and physiology

## Mechanical Features

### Stat Bonuses
- **Anequinan**: Movement speed, stealth, combat effectiveness, environmental resistance
- **Pellitine**: Social influence, trade bonuses, diplomatic advantages, craftsmanship
- **Quadrupedal**: Breed-specific enhancements matching their roles and abilities

### Material Requirements  
- **Anequinan**: Practical materials (leather, basic metals, fabric)
- **Pellitine**: Refined materials (fine fabrics, precious metals)
- **Quadrupedal**: Specialized materials based on function (magical components, utility gear)

### Research Prerequisites
- Basic items: ComplexClothing, Smithing
- Advanced items: PlateArmor
- Maintains progression balance with existing content

## Lore Accuracy

The system faithfully represents Elder Scrolls lore:

- **Regional Differences**: Accurately depicts the cultural divide between northern and southern Elsweyr
- **Breed Physiology**: Acknowledges the unique needs of quadrupedal Khajiit breeds  
- **Cultural Elements**: Incorporates authentic details about nomadic vs. settled lifestyles
- **Material Culture**: Uses appropriate crafting methods and materials for each region

## Usage

Players can craft these items using the standard RimWorld crafting system, with items requiring appropriate research and skill levels. The style system allows these items to be selected in faction outfit preferences, and the `allowedRaces` restrictions ensure quadrupedal items are only usable by the appropriate Khajiit breeds.