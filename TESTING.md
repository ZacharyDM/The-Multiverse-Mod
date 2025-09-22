# Multiverse Mod Testing Guide

This document outlines basic testing procedures for the Multiverse Mod.

## Manual Testing Checklist

### Basic Functionality
- [ ] Mod loads without errors
- [ ] All race definitions load correctly
- [ ] Faction definitions work as expected
- [ ] Items and weapons can be crafted
- [ ] Buildings can be constructed
- [ ] Research projects are available

### Race Testing
#### Star Wars Races
- [ ] Galactic Human spawns with correct traits
- [ ] Twi'lek has proper appearance and abilities
- [ ] Rodian has hunting bonuses
- [ ] Zabrak has mental resilience
- [ ] Chiss has tactical bonuses
- [ ] Wookiee has strength and loyalty traits

#### Elder Scrolls Races
- [ ] Nord has frost resistance
- [ ] Imperial has social bonuses
- [ ] Breton has magic affinity
- [ ] Redguard has sword mastery
- [ ] Altmer has magical superiority
- [ ] Bosmer has archery skills
- [ ] Orsimer has physical strength
- [ ] Khajiit has agility and trading
- [ ] Argonian has disease resistance

### Faction Testing
- [ ] Star Wars factions appear in world generation
- [ ] Elder Scrolls factions work with existing Dunmer system
- [ ] Faction relationships are logical
- [ ] Pawn kinds spawn with correct equipment

### Item Testing
- [ ] Lightsaber can be crafted with kyber crystals
- [ ] Blaster functions as ranged weapon
- [ ] Daedric weapons have enhanced damage
- [ ] Dwarven items work correctly
- [ ] Food items provide proper nutrition
- [ ] Sujamma provides temporary effects

### Building Testing
- [ ] Lightsaber forge functions properly
- [ ] Holo table provides correct benefits
- [ ] Daedric altar allows weapon crafting
- [ ] Dwarven automaton defends properly
- [ ] Telvanni tower provides power

### Research Testing
- [ ] All research projects are accessible
- [ ] Prerequisites work correctly
- [ ] Unlocked technologies function
- [ ] Research costs are balanced

### Integration Testing
- [ ] New content integrates with base game
- [ ] No conflicts with existing systems
- [ ] Performance impact is minimal
- [ ] Save/load compatibility maintained

## Automated Testing

Currently, no automated tests are implemented. Future versions should include:
- Unit tests for core functionality
- Integration tests with base game systems
- Performance benchmarks
- Compatibility tests with popular mods

## Known Issues

Document any issues discovered during testing here.

## Test Environment

- RimWorld Version: 1.6
- Mod Version: Current development
- Test Date: [Date of testing]
- Tester: [Name]

## Reporting Issues

Issues should be reported to the GitHub repository with:
1. Clear description of the problem
2. Steps to reproduce
3. Expected vs actual behavior
4. Screenshots if applicable
5. Log files if crashes occur