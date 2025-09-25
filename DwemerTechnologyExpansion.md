# Dwemer Technology Expansion Documentation

This documentation covers the Dwarven Metal resource system and Dwemeri style implementations added to The Multiverse Mod, providing advanced technological options gated behind faction relationships and research progression.

## Overview

The Dwemer Technology expansion introduces **dwarven metal** as a unique resource with **trade-only availability** and **faction-gated technology access**:

### Core Features
- **Dwarven Metal Resource** - Rare, highly valuable metal with superior properties
- **Dwemer Technologists Faction** - Controls access to advanced Dwemer technology
- **3-Tier Research Progression** - Metallurgy → Crafting → Engineering
- **8 Unique Items** - Across apparel, weapons, and buildings categories

### Dwemeri Style Categories
- **Apparel (4 items)** - Engineering robes, mechanical armor, scholar spectacles, work boots
- **Weapons (3 items)** - Crossbow, war hammer, precision blade  
- **Buildings (4 items)** - Steam forge, observatory, mechanical door, precision workbench

## Resource System

### Dwarven Metal (Raw)
- **Market Value**: 450 gold per unit
- **Availability**: Trade-only, no mining or natural spawning
- **Rarity**: Extremely limited supply
- **Properties**: Superior to conventional materials

### Dwarven Metal Ingot (Processed)
- **Market Value**: 750 gold per unit
- **Material Stats**: 2.8x hit points, 1.8x sharp damage multiplier
- **Crafting**: Requires processing raw dwarven metal
- **Uses**: Superior crafting material for all applications

## Faction Integration

### Dwemer Technologists Faction
- **Race**: Dwemer only
- **Tech Level**: Industrial
- **Relationship**: Required for technology access
- **Spawning**: Rare, limited settlements
- **Leader**: Chief Engineer

**Key Mechanics:**
- Controls access to Dwemer technology through quest/relationship requirements
- Cannot stage attacks or sieges (peaceful faction)
- Industrial tech level reflects their advanced capabilities

## Research Progression

### Tier 1: Dwemer Metallurgy
- **Cost**: 3,500 research points
- **Prerequisites**: Smithing, Machining
- **Tech Level**: Industrial
- **Unlocks**: Basic dwarven metal processing
- **Requirements**: Hi-tech research bench, multi-analyzer

### Tier 2: Dwemer Crafting Techniques  
- **Cost**: 4,800 research points
- **Prerequisites**: Dwemer Metallurgy, Complex Clothing
- **Tech Level**: Industrial
- **Unlocks**: Dwemeri apparel, weapons, basic buildings
- **Requirements**: Hi-tech research bench, multi-analyzer

### Tier 3: Dwemer Engineering
- **Cost**: 6,500 research points
- **Prerequisites**: Dwemer Crafting, Fabrication
- **Tech Level**: Spacer
- **Unlocks**: Advanced buildings, legendary equipment
- **Requirements**: Hi-tech research bench, multi-analyzer

## Equipment Overview

### Apparel Items

#### Dwemeri Engineering Robes
- **Protection**: Moderate (0.35 sharp, 0.15 blunt armor)
- **Bonuses**: +25% research speed, +15% work speed, +20% construction
- **Cost**: 85 fabric + 2 dwarven metal ingots + 1 component
- **Research**: Dwemer Crafting

#### Dwemeri Mechanical Armor
- **Protection**: Excellent (1.25 sharp, 0.85 blunt armor) 
- **Bonuses**: +10% move speed, +20% work speed, +25 carry capacity
- **Cost**: 150 metallic + 8 dwarven metal ingots + 3 components + 25 steel
- **Research**: Dwemer Engineering

#### Dwemeri Scholar's Spectacles
- **Protection**: Light (0.10 sharp, 0.05 blunt armor)
- **Bonuses**: +35% research speed, +15% shooting accuracy, +20% surgery
- **Cost**: 1 dwarven metal ingot + 1 component + 10 gold
- **Research**: Dwemer Crafting

#### Dwemeri Work Boots
- **Protection**: Good (0.25 sharp, 0.35 blunt, 0.45 heat armor)
- **Bonuses**: +5% move speed, +10% work speed, +20% mining speed
- **Cost**: 45 leather + 1 dwarven metal ingot + 15 steel
- **Research**: Dwemer Crafting

### Weapon Items

#### Dwemeri Crossbow
- **Type**: Ranged weapon (arrows)
- **Accuracy**: Excellent across all ranges
- **Range**: 32 cells
- **Special**: Mechanical loading system, precision targeting
- **Research**: Dwemer Crafting

#### Dwemeri War Hammer
- **Type**: Two-handed blunt weapon
- **Damage**: 28 power, 0.45 armor penetration
- **Special**: Steam-powered impact amplification
- **Penalty**: -15% move speed, -10% hit chance
- **Research**: Dwemer Crafting

#### Dwemeri Precision Blade
- **Type**: One-handed sword
- **Damage**: 18 stab/22 cut, 0.35/0.25 armor penetration
- **Bonuses**: +5% move speed, +15% hit chance, +8% dodge
- **Special**: Self-maintaining edge, kinetic energy channeling
- **Research**: Dwemer Engineering

### Building Items

#### Dwemeri Steam Forge
- **Type**: Advanced crafting station
- **Size**: 3x1 tiles
- **Features**: Heat generation, enhanced crafting capabilities
- **Cost**: 15 dwarven metal ingots + 80 steel + 8 components
- **Research**: Dwemer Engineering

#### Dwemeri Observatory
- **Type**: Research facility
- **Size**: 4x4 tiles
- **Bonus**: +35% research speed factor
- **Beauty**: 35 beauty value
- **Research**: Dwemer Engineering

#### Dwemeri Mechanical Door
- **Type**: Heavy security door
- **Durability**: 280 hit points
- **Features**: Precision gear operation, beautiful appearance
- **Cost**: 6 dwarven metal ingots + 25 steel + 2 components
- **Research**: Dwemer Crafting

#### Dwemeri Precision Workbench
- **Type**: Enhanced crafting table
- **Size**: 3x1 tiles
- **Bonus**: +35% work table speed factor
- **Features**: Built-in precision tools and measurements
- **Research**: Dwemer Crafting

## File Structure

```
Defs/
├── FactionDefs/
│   └── DunmerFactions.xml           # Dwemer Technologists faction
├── ResearchProjectDefs/
│   └── DwemerTechnology.xml         # Three-tier research progression
├── RecipeDefs/
│   └── DwemerMetallurgyRecipes.xml  # Metal processing recipes
├── ThingDefs/
│   ├── Items/
│   │   └── DwarvenMetal.xml         # Raw metal and ingot definitions
│   ├── Apparel/Dwemeri/
│   │   └── DwemeriApparel.xml       # Four apparel items
│   ├── Weapons/
│   │   └── DwemeriWeapons.xml       # Three weapon types
│   └── Buildings/
│       └── DwemeriBuildings.xml     # Four building types
```

## Gameplay Integration

### Acquisition Strategy
1. **Establish Trade Relations** - Find traders carrying dwarven metal
2. **Locate Dwemer Technologists** - Build relationship with faction
3. **Research Progression** - Unlock technologies in sequence
4. **Master Crafting** - High skill requirements for all items

### Tactical Considerations
- **High Investment Costs** - Expensive materials and research
- **Faction Dependence** - Requires maintaining good relations
- **Skill Requirements** - Demands highly skilled crafters
- **Superior Performance** - Significant advantages justify costs

### Economic Impact
- **Trade Focus** - Encourages active trading and diplomacy
- **Luxury Market** - Creates high-value item category
- **Research Investment** - Long-term progression goals
- **Skill Development** - Incentivizes crafter specialization

## Lore Integration

This expansion integrates seamlessly with existing Elder Scrolls lore by:

- **Dwemer Heritage** - Builds on established Dwemer racial characteristics
- **Technological Mystery** - Maintains the mystique of lost Dwemer knowledge
- **Material Authenticity** - Reflects canonical dwarven metal properties
- **Cultural Consistency** - Aligns with Dwemer engineering traditions

The system respects the lore principle that Dwemer technology should be rare, valuable, and difficult to reproduce, while providing meaningful gameplay progression for dedicated players.

## Technical Notes

- All definitions use standard RimWorld XML format
- Research prerequisites prevent early access to advanced technology
- High skill requirements ensure appropriate progression gates
- Superior material stats justified by rarity and difficulty of acquisition
- Faction integration provides natural quest/relationship hooks for future content