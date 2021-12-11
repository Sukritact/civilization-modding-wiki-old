---
title: The Modifier System - About
description: An introduction to Civ VI's modifier system
published: true
date: 2021-12-11T23:06:12
tags: database modding, modifiers, requirements
editor: markdown
dateCreated: 2021-12-10T14:19:34
---

# The Modifier System
## Introduction
The Modifier System is the way most effects and abilities in Civilization VI are implemented. While limited in some ways, they can be remarkably powerful and are central to gameplay modding in Civilization VI.

## Anatomy of a Modifier
A modifier is composed of a **Modifier Type**, a series of **Modifier Arguments**, an **Owner**, a **Subject**. Each modifier in the database is identified by a unique **Modifier ID**.

### Modifier Type
**Modifier Types** are a combination of an **Effect Type** and a **Collection Type**. The effect type determines what the Modifier will do, and the collection type determines what objects a modifier affects. Modifier Types can be found in the **DynamicModifiers** table of the database.

For instance the `MODIFIER_PLAYER_ADJUST_PLOT_YIELD` modifier type is a combination of the `EFFECT_ADJUST_PLOT_YIELD` effect type and the `COLLECTION_PLAYER_PLOT_YIELDS` collection type. So a modifier of this type will adjust the plot yield of all plots owned by the player that owns this modifier.

### Modifier Arguments

**Modifier Arguments** control the specific effects of a modifier. They are listed in the **ModifierArguments** table and are tied to specific modifiers by their **Modifier ID**. What "arguments" are available to a modifier is defined by its **Effect Type**.

For instance `EFFECT_ADJUST_PLOT_YIELD` has two arguments: YieldType—say Food—and an Amount—say 2.

### Owner and Subject

**The Owner and Subject** are both **game objects** (e.g., a Player, a Tile Improvement, or a Unit). The Owner is whatever object the modifier is attached to. The Subject is whatever object the modifier affects.

The Owner and Subject can be different objects, or they can be the same object (i.e., an object can "own" a modifier that affects itself).

The Owner is not explicitly defined as part of the modifier's definition: instead you can tell certain object types (e.g, a specific District type or a specific Civilization), to spawn with a modifier. The Subject/s of a modifier is determined by the Modifier Type.

The Subject is determined by a combination of the Owner and the modifier's **Collection Type**. `COLLECTION_PLAYER_PLOT_YIELDS` targets Plot/Hexes owned by the Player which owns the modifier.

Both Objects and Subjects can have [Requirement Sets](database-modding/modifier-system/requirement-sets.md) associated with them. Requirement Sets are a collection of [Requirements](database-modding/modifier-system/requirements.md) which must be met before the Modifier will take effect. For instance, you can use `PLOT_HAS_TUNDRA_REQUIREMENTS` as a Subject Requirement Set to restrict a modifier to affecting objects on tiles with Tundra.