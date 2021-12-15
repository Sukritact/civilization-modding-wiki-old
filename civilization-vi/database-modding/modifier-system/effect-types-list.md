---
title: List of Effect Types
description: 
published: true
date: 2021-12-15T00:31:48.273Z
tags: database modding, modifiers, civilization vi
editor: markdown
dateCreated: 2021-12-13T17:48:41.575Z
---

# List of Effect Types
This table has been adapted from [ChimpanG's Modding Companion](https://docs.google.com/spreadsheets/d/1hQ8zlEHl1nfjCWvKqOlkDACezu5-igfQkVcOxeE_KG0/edit#gid=1678767919).

---

<div style="width: auto; overflow-x: scroll;">
<table>
<thead>
	<tr>
		<th>Status</th>
		<th>EffectType</th>
		<th>Class</th>
		<th colspan="3">Arguments</th>
		<th>Notes</th>
		<th colspan="4">Availability</th>
	</tr>
	<tr>
		<th>&nbsp;</th>
		<th>&nbsp;</th>
		<th>&nbsp;</th>
		<th>Name</th>
		<th>Type</th>
		<th>Value</th>
		<th>&nbsp;</th>
		<th>Vanilla</th>
		<th>XP1</th>
		<th>XP2</th>
		<th>NFP</th>
	</tr>
</thead>
<tbody>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ACTIVATE_VOLCANOES</td>
	<td rowspan="1"></td>
	<td>PercentageActive</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_BELIEF</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADD_CULTURE_BOMB_TRIGGER</td>
	<td rowspan="3">PLAYERS</td>
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADD_DIPLO_VISIBILITY</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>Source</td>
	<td>String</td>
	<td>SOURCE_ALLY<br>SOURCE_DELEGATE<br>SOURCE_GREAT_PERSON_JOURNALISM<br>SOURCE_SPY<br>SOURCE_TECH<br>SOURCE_TRADER<br>SOURCE_TRADING_POST_TRAIT<br>SOURCE_TRAIT</td>
</tr>
<tr class="Argument">
	<td>SourceType</td>
	<td>String</td>
	<td>DIPLO_SOURCE_ALL_NAMES<br>DIPLO_SOURCE_FEMALE_ONLY</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADD_DIPLOMATIC_ACTION_OVERRIDE</td>
	<td rowspan="2">PLAYERS</td>
	<td>CivicType</td>
	<td>String</td>
	<td>[Civics.CivicType]</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>DiplomaticAction</td>
	<td>String</td>
	<td>[DiplomaticActions.DiplomaticActionType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADD_DIPLOMATIC_COMBAT_MODIFIER</td>
	<td rowspan="4">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
</tr>
<tr class="Argument">
	<td>DiplomaticYieldSource</td>
	<td>String</td>
	<td>CITY_CAPTURED<br>LIBERATION<br>LIBERATION_WAR_INITIATED<br>PROTECTORATE_WAR_INITIATED<br>SURPRISE_WAR_INITIATED<br>TERRITORIAL_EXPANSION_WAR_INITATED<br>WAR_DECLARATION_INITIATED<br>WAR_DECLARATION_RECEIVED</td>
</tr>
<tr class="Argument">
	<td>ReligiousOnly</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TurnsActive</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADD_DIPLOMATIC_MOVEMENT_MODIFIER</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>DiplomaticYieldSource</td>
	<td>String</td>
	<td>CITY_CAPTURED<br>LIBERATION<br>LIBERATION_WAR_INITIATED<br>PROTECTORATE_WAR_INITIATED<br>SURPRISE_WAR_INITIATED<br>TERRITORIAL_EXPANSION_WAR_INITIATED<br>WAR_DECLARATION_INITIATED<br>WAR_DECLARATION_RECEIVED</td>
</tr>
<tr class="Argument">
	<td>TurnsActive</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_ADD_DIPLOMATIC_YIELD_MODIFIER</td>
	<td rowspan="5">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
</tr>
<tr class="Argument">
	<td>DiplomaticYieldSource</td>
	<td>String</td>
	<td>CITY_CAPTURED<br>LIBERATION<br>LIBERATION_WAR_INITIATED<br>PROTECTORATE_WAR_INITIATED<br>SURPRISE_WAR_INITIATED<br>TERRITORIAL_EXPANSION_WAR_INITIATED<br>WAR_DECLARATION_INITIATED<br>WAR_DECLARATION_RECEIVED</td>
</tr>
<tr class="Argument">
	<td>StackWithOtherDiploYieldModifiers</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TurnsActive</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_EXPENDED_GREAT_PERSON_TILES</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADD_PLAYER_BELIEF_YIELD</td>
	<td rowspan="4">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
</tr>
<tr class="Argument">
	<td>BeliefYieldType</td>
	<td>String</td>
	<td>BELIEF_YIELD_PER_CITY<br>BELIEF_YIELD_PER_DISTRICT<br>BELIEF_YIELD_PER_FOLLOWER<br>BELIEF_YIELD_PER_FOREIGN_CITY<br>BELIEF_YIELD_PER_FOREIGN_FOLLOWER</td>
</tr>
<tr class="Argument">
	<td>PerXItems</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_PLAYER_FAVOR</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_PLAYER_PROJECT_AVAILABILITY</td>
	<td rowspan="1"></td>
	<td>ProjectType</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_PLAYER_SEQUESTERED_CARBON</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_PLAYER_UPGRADE_MILITARY_FORMATION_ON_CITY_CONQUEST</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_ADD_RELIGIOUS_BELIEF_YIELD</td>
	<td rowspan="5">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
</tr>
<tr class="Argument">
	<td>BeliefYieldType</td>
	<td>String</td>
	<td>BELIEF_YIELD_PER_CITY<br>BELIEF_YIELD_PER_DISTRICT<br>BELIEF_YIELD_PER_FOLLOWER<br>BELIEF_YIELD_PER_FOREIGN_CITY<br>BELIEF_YIELD_PER_FOREIGN_FOLLOWER</td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>PerXItems</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_RELIGIOUS_BUILDING</td>
	<td rowspan="1">PLAYERS</td>
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADD_RELIGIOUS_BUILDING_MULTIPLIER</td>
	<td rowspan="3">PLAYERS</td>
	<td>Founder</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>Multiplier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADD_RELIGIOUS_UNIT</td>
	<td rowspan="1">PLAYERS</td>
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_ADDITIONAL_PILLAGING</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="Argument">
	<td>PlunderType</td>
	<td>String</td>
	<td>PLUNDER_CULTURE<br>PLUNDER_FAITH<br>PLUNDER_GOLD<br>PLUNDER_HEAL<br>PLUNDER_SCIENCE</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_ACCUMULATING_BONUS</td>
	<td rowspan="3">PLAYERS</td>
	<td>BonusType</td>
	<td>String</td>
	<td>[GovernmentBonusNames.GovernmentBonusType]</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>Increment</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Interval</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_ACTIVE_BUILDING_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ADD_AMENITY_PER_ADJACENT_LUXURY</td>
	<td rowspan="1">CITIES</td>
	<td>AddAmenity</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ADJACENT_CITY_RIVER_BUILDING_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ADJACENT_CITY_RIVER_DISTRICT_PRODUCTION</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ADJACENT_LEVIED_UNIT_COMBAT_BONUS</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_ALL_BUILDING_PRODUCTION_MODIFIER</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>IsWonder</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_BUILDINGS_PURCHASE_COST</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_DISTRICT_PRODUCTION_MODIFIER</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_DISTRICTS_CULTURE_BOMB</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_DISTRICTS_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_DISTRICTS_PURCHASE_COST</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_GREAT_WORKS_TOURISM_MODIFIER</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_GREAT_WORKS_YIELDS_MODIFIER</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_PROJECTS_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALL_UNIT_PRODUCTION_MODIFIER</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_ALL_UNITS_PURCHASE_COST</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>IncludeCivilian</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>UnitDomain</td>
	<td>String</td>
	<td>DOMAIN_AIR<br>DOMAIN_LAND<br>DOMAIN_SEA</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALLIANCE_PLAYER_STRENGTH_MODIFIER</td>
	<td rowspan="1">COMBATS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALLIANCE_POINTS_FOR_COMMON_ENEMY_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALLIANCE_POINTS_FOR_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_ALLIANCE_POINTS_FOR_TRADE_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_ATTACKER_STRENGTH_MODIFIER</td>
	<td rowspan="2">COMBATS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>Stack</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_AUTO_THEMED_BUILDINGS_WITH_X_SLOTS</td>
	<td rowspan="2"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>IsWonder</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_BANNED_DIPLOMATIC_ACTIONS</td>
	<td rowspan="2"></td>
	<td>Banned</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>DiplomaticActionType</td>
	<td>String</td>
	<td>[DiplomaticActions.DiplomaticActionType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_BANNED_DIPLOMATIC_ACTIONS_SPECIFIC_CIVILIZATION</td>
	<td rowspan="2"></td>
	<td>CivilizationType</td>
	<td>String</td>
	<td>[Civilizations.CivilizationType]</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>DiplomaticActionType</td>
	<td>String</td>
	<td>[DiplomaticActions.DiplomaticActionType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_BONUS_RATE</td>
	<td rowspan="3">PLAYERS</td>
	<td>BonusRate</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>BonusType</td>
	<td>String</td>
	<td>[GovernmentBonusNames.GovernmentBonusType]</td>
</tr>
<tr class="Argument">
	<td>CityStatesOnly</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_BUILDING_AMENITY</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_BUILDING_HOUSING</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_BUILDING_PRODUCTION</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_BUILDING_PURCHASE_COST</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_BUILDING_SPREAD_CHARGES</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_BUILDING_YIELD_CHANGE</td>
	<td rowspan="4">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
</tr>
<tr class="Argument">
	<td>CityStatesOnly</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_BUILDING_YIELD_MODIFIER</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_BUILDING_YIELD_MODIFIERS_FOR_DISTRICT</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITIES_FRESHWATER_HOUSING_BONUS</td>
	<td rowspan="1">CITIES</td>
	<td>HasBonus</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITIES_HAS_URBAN_DEFENSES</td>
	<td rowspan="1">CITIES</td>
	<td>DefenseValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CAN_FAITH_PURCHASE_DISTRICTS</td>
	<td rowspan="1">CITIES</td>
	<td>CanPurchase</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_AIR_DEFENSE_BONUS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_CITY_ALL_MILITARY_UNITS_PRODUCTION</td>
	<td rowspan="4">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>EndEra</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="Argument">
	<td>PromotionClass</td>
	<td>String</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
</tr>
<tr class="Argument">
	<td>StartEra</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_ALL_YIELDS_CHANGE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_ALLOWED_IMPROVEMENT</td>
	<td rowspan="1">CITIES</td>
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_ALLOWED_INCOMING_REGIONAL_STACKING</td>
	<td rowspan="1">CITIES</td>
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_ALWAYS_LOYAL</td>
	<td rowspan="1">CITIES</td>
	<td>AlwaysLoyal</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_AMENITIES_FROM_CITY_STATES</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_AMENITIES_FROM_GOVERNORS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_AMENITIES_FROM_GREAT_PEOPLE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_AMENITIES_FROM_RELIGION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_APPEAL</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_ATTACKS_PER_TURN</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_CAN_PURCHASE_DISTRICTS</td>
	<td rowspan="1">CITIES</td>
	<td>CanPurchase</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_COMBAT_BONUS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_CORPS_ARMY_PRODUCTION</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>UnitDomain</td>
	<td>String</td>
	<td>DOMAIN_AIR<br>DOMAIN_LAND<br>DOMAIN_SEA</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_CULTURE_BORDER_EXPANSION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_ENTERTAINMENT</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_ENTERTAINMENT_FROM_WONDER_ADJACENT_TO_LAKE</td>
	<td rowspan="1">CITIES</td>
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_EXTRA_ACCUMULATION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_EXTRA_ACCUMULATION_FOR_STRATEGIC_DIVERSITY</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_EXTRA_ACCUMULATION_SPECIFIC_RESOURCE</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_EXTRA_AMENITY_FOR_LUXURY_DIVERSITY</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_EXTRA_DISTRICTS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_FREE_POWER</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>SourceType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_FRIENDLY_COMBAT_BONUS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_GOLD_FROM_CITIZENS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_GREAT_PERSON_POINTS_MODIFIER</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_CITY_GREATWORK_YIELD</td>
	<td rowspan="4">CITIES</td>
	<td>GreatWorkObjectType</td>
	<td>String</td>
	<td>[GreatWorkObjectTypes.GreatWorkObjectType]</td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>ScalingFactor</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldChange</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_GROWTH</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_CITY_HAPPINESS_GREAT_PERSON</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>GreatPersonClassType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
</tr>
<tr class="Argument">
	<td>HappinessType</td>
	<td>String</td>
	<td>[Happinesses.HappinessType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_CITY_HAPPINESS_YIELD</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>HappinessType</td>
	<td>String</td>
	<td>[Happinesses.HappinessType]</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_HIT_POINTS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_HOUSING_FROM_GREAT_PEOPLE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_HOUSING_PER_DISTRICT</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_IDENTITY_PER_CITIZEN</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_IDENTITY_PER_TURN</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_IDENTITY_PRESSURE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_CITY_IDENTITY_PRESSURE_FROM_AGES</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_IGNORE_STRATEGIC_RESOURCE_REQUIREMENTS</td>
	<td rowspan="1">CITIES</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_IMPROVEMENT_TOURISM</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_INNER_DEFENSE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_NATIONAL_PARK_TOURISM</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_NO_CULTURE_BORDER_EXPANSION</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_OUTER_DEFENSE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_POPULATION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_POPULATION_UNIT_CREATED</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_PREVENT_BYPASS_OUTER_DEFENSES</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_PREVENT_MELEE_ATTACK_OUTER_DEFENSES</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_PRODUCTION_BUILDING</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_PRODUCTION_DISTRICT</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_PRODUCTION_UNIT</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_CITY_PROPERTY</td>
	<td rowspan="1">CITIES</td>
	<td>PropertyName</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RANGED_STRIKE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RELIGION_EXTRA_PROMOTIONS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RELIGION_IGNORE_COMBAT</td>
	<td rowspan="1">CITIES</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RELIGION_IGNORE_PRESSURE</td>
	<td rowspan="1">CITIES</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RELIGION_ON_CAPTURE</td>
	<td rowspan="1">CITIES</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RELIGION_PRESSURE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RELIGIOUS_COMBAT_BONUS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RELIGIOUS_HEAL</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_RESOURCE_HARVEST_BONUS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_REQUIRED_POWER</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_SETTLER_CONSUME_POP</td>
	<td rowspan="2">CITIES</td>
	<td>Enabled</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Religious</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_SIEGE_PROTECTION</td>
	<td rowspan="1">CITIES</td>
	<td>Protected</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_SPY_BONUS</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_STATE_TRADE_ROUTE_DISTRICT_YIELD</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_STRATEGIC_RESOURCE_REQUIREMENT_MODIFIER</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_ADJUST_CITY_TOURISM</td>
	<td rowspan="5">CITIES</td>
	<td>BoostsWonders</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>GreatWorkObjectType</td>
	<td>String</td>
	<td>[GreatWorkObjectTypes.GreatWorkObjectType]</td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="Argument">
	<td>Religious</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ScalingFactor</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TOURISM_LATE_ERAS</td>
	<td rowspan="2">CITIES</td>
	<td>MinimumEra</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Modifier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_TOURISM_PER_FEATURE</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_FOR_DOMESTIC</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_FOR_INTERNATIONAL</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_PER_DESTINATION_LUXURY_RESOURCE_FOR_INTERNATIONAL</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_PER_DESTINATION_STRATEGIC_RESOURCE_FOR_DOMESTIC</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_PER_DESTINATION_STRATEGIC_RESOURCE_FOR_INTERNATIONAL</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_PER_LOCAL_BONUS_RESOURCE_FOR_DOMESTIC</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_PER_LOCAL_BONUS_RESOURCE_FOR_INTERNATIONAL</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="2">❔</td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_PER_LOCAL_LUXURY_RESOURCE_FOR_INTERNATIONAL</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="2">❔</td>
	<td rowspan="2">EFFECT_ADJUST_CITY_TRADE_ROUTE_YIELD_PER_LOCAL_STRATEGIC_RESOURCE_FOR_INTERNATIONAL</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_CITY_UNIT_MAX_LEVEL</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_CHANGE</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_FROM_FOREIGN_TRADE_ROUTES_PASSING_THROUGH</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_FROM_POWERED_BUILDING</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_MODIFIER</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="2">❔</td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_MODIFIER_FROM_FAITH</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_MODIFIER_PER_GOVERNOR_TITLE</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_PER_DISTRICT</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_PER_FLOOD</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_PER_MAJOR_TRADE_PARTNER</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CITY_YIELD_PER_POPULATION</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="3">❔</td>
	<td rowspan="3">EFFECT_ADJUST_CITY_YIELD_PER_TERRAIN_TYPE</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>TerrainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CITY_YIELD_PER_TERRAIN_CLASS_CITIES</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_CITY_YIELD_PER_TERRAIN_CLASS_CITIES_IMPROVEMENT</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CIVIC_BOOST</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_CO2_GENERATION_REDUCTION</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>ResourceUsageType</td>
	<td>String</td>
	<td>RESOURCE_USAGE_UNIT</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_CORPS_ARMY_MODIFIED_STRENGTH</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Corps</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Domain</td>
	<td>String</td>
	<td>DOMAIN_AIR<br>DOMAIN_LAND<br>DOMAIN_SEA</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_CORPS_ARMY_PREREQ</td>
	<td rowspan="3">PLAYERS</td>
	<td>CivicType</td>
	<td>String</td>
	<td>[Civics.CivicType]</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Corps</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Domain</td>
	<td>String</td>
	<td>DOMAIN_AIR<br>DOMAIN_LAND<br>DOMAIN_SEA</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_CULTURE_BOMB_CONVERTS_CITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>ConvertsCity</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DEFENDER_STRENGTH_MODIFIER</td>
	<td rowspan="1">COMBATS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DIPLOMATIC_ACTION_PREFERENCE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Action</td>
	<td>String</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Favored</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_DIPLOMATIC_SCORE</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISABLE_HEALING</td>
	<td rowspan="2">PLAYERS</td>
	<td>Disable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Foreign</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISABLE_INFLUENCE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Disable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_DISABLE_PATRONAGE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Disable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISABLE_SETTLING</td>
	<td rowspan="2">PLAYERS</td>
	<td>Disabled</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Multiplicative</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_ADJACENT_NATURAL_WONDER_PRODUCTION</td>
	<td rowspan="2">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>FeatureType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_AMENITY</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_ATTACK_RANGE</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_BASE_YIELD_CHANGE</td>
	<td rowspan="2">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_BUILDING_PRODUCTION</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_EXTRA_ENTERTAINMENT</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_EXTRA_REGIONAL_ENTERTAINMENT</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_EXTRA_REGIONAL_RANGE</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_EXTRA_REGIONAL_YIELD</td>
	<td rowspan="2">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_GREAT_PERSON_POINTS</td>
	<td rowspan="2">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>GreatPersonClassType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_HOUSING</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_PREREQ</td>
	<td rowspan="2">DISTRICTS</td>
	<td>DistrictType</td>
	<td>String</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>TechType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_PRODUCTION</td>
	<td rowspan="2">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_PROPERTY</td>
	<td rowspan="1">DISTRICTS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_TOURISM_ADJACENCY_YIELD_MOFIFIER</td>
	<td rowspan="1">DISTRICTS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DISTRICT_TOURISM_CHANGE</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_DISTRICT_YIELD_BASED_ON_ADJACENCY_BONUS</td>
	<td rowspan="3">DISTRICTS</td>
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>YieldTypeToGrant</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="Argument">
	<td>YieldTypeToMirror</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_ADJUST_DISTRICT_YIELD_BASED_ON_APPEAL</td>
	<td rowspan="5">CITIES</td>
	<td>Description</td>
	<td>String</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>RequiredAppeal</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldChange</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_YIELD_CHANGE</td>
	<td rowspan="2">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_DISTRICT_YIELD_MODIFIER</td>
	<td rowspan="2">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DUPLICATE_FIRST_INFLUENCE_TOKEN</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DUPLICATE_INFLUENCE_TOKEN_WHEN_RIVAL_GOVERNMENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DUPLICATE_INFLUENCE_TOKEN_WHEN_SAME_RELIGION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_DUPLICATE_INFLUENCE_TOKEN_WHEN_TRADE_ROUTE_TO</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_EXTRA_ACCUMALATION_TERRAIN</td>
	<td rowspan="2"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_EXTRA_GREAT_WORK_SLOTS</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
</tr>
<tr class="Argument">
	<td>GreatWorkSlotType</td>
	<td>String</td>
	<td>[GreatWorkSlotTypes.GreatWorkSlotType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_EXTRA_HEAL_GOVERNOR</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_EXTRA_STARTING_POPULATION_OFF_HOME_CONTINENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_EXTRA_UNIT_COPY</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_EXTRA_UNIT_COPY_TAG</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Tag</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_FEATURE_APPEAL_MODIFIER</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>FeatureType</td>
	<td>String</td>
	<td>[Features.FeatureType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_FEATURE_NO_IMPROVEMENT_APPEAL_GOVERNOR</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_FEATURE_PREREQ</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_FLAT_BONUS</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>BonusType</td>
	<td>String</td>
	<td>[GovernmentBonusNames.GovernmentBonusType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_FOLLOWER_YIELD_MODIFIER</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_FORBID_LAND_ROUTE</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_FULL_ACCESS_ONE_STRATEGIC</td>
	<td rowspan="1">PLAYERS</td>
	<td>Access</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_FREE_CIVIC_BOOST_FIRST_TRADING_POST_EACH_CIV</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_FREE_TECH_BOOST_FIRST_TRADING_POST_EACH_CIV</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_GAINS_ALL_FOLLOWER_BELIEFS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_GAINS_FOUNDER_BELIEF_MAJORITY_RELIGION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_GAME_REALISM_SETTING</td>
	<td rowspan="1"></td>
	<td>RealismSettingType</td>
	<td>String</td>
	<td>[RealismSettings.RealismSettingType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_GAME_PROPERTY</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GLOBAL_WMD_STOCKPILE</td>
	<td rowspan="2"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>TargetOnly</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GOLD_DISPERSAL</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Improvement</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GOVERNMENT_SLOTS</td>
	<td rowspan="2"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>GovernmentSlotType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_GOVERNOR_ALLIANCE_POINTS</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GOVERNOR_GRIEVENCE_SCORE</td>
	<td rowspan="2"></td>
	<td>Score</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Turns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_GOVERNOR_IDENTITY_PRESSURE</td>
	<td rowspan="3">GOVERNORS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>DomesticCities</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ForeignCities</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GREAT_PEOPLE_POINTS_PER_KILL</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>GreatPersonClassType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GREAT_PERSON_GUARANTEE</td>
	<td rowspan="2">PLAYERS</td>
	<td>EraType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>GreatPersonClassType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GREAT_PERSON_PATRONAGE_DISCOUNT_PERCENT</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GREAT_PERSON_POINTS</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>GreatPersonClassType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_GREAT_PERSON_POINTS_PERCENT</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>GreatPersonClassType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_GREAT_PERSON_POINTS_REFUND_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_GREAT_WORK_OBJECT_NO_TOURISM</td>
	<td rowspan="1"></td>
	<td>NoTourism</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_GREAT_WORK_OBJECT_TOURISM_MODIFIER</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_HEAL_CHARGES</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_IDENTITY_PER_TURN_FROM_NEARBY_GREAT_WORKS</td>
	<td rowspan="3"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>DomesticCities</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ForeignCities</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_IGNORE_IDENTITY_PRESSURE</td>
	<td rowspan="1"></td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_IMPROVEMENT_AMENITY</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_IMPROVEMENT_GOODY_HUT</td>
	<td rowspan="2">PLAYERS</td>
	<td>GoodyHutImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_IMPROVEMENT_HOUSING</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_IMPROVEMENT_PROPERTY</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_IMPROVEMENT_VALID_TERRAIN</td>
	<td rowspan="2"></td>
	<td>ImprovementType</td>
	<td>String</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_INFLUENCE_POINTS_PER_TURN</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_INQUISITION_START_CHARGES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_LOYALTY_FROM_GREAT_WORKS_CITIZENS</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_MOST_ADVANCED_STRATEGIC_RESOURCE_COUNT</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_MULTIPLY_TREASURY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_NATURAL_WONDER_AMENITY</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_NATURAL_WONDER_RELIC</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_NO_FRESH_WATER_HOUSING</td>
	<td rowspan="1">CITIES</td>
	<td>NoHousing</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_NO_GREAT_PERSON_POINTS</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_NUM_UNITS_SUPPORTED</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_OWNED_BONUS_RESOURCE_EXTRA_AMENITIES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_OWNED_LUXURY_EXTRA_AMENITIES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_NUMBER_ALLIES_UNIT_COMBAT_BONUS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_ADD_CHOP_YIELD</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ADJUST_ENVOYS_NON_SPECIALTY</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ALL_ALLIANCES_PROVIDE_SHARED_VIS</td>
	<td rowspan="1">PLAYERS</td>
	<td>ShareVis</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ALLIED_WAR_DISCOUNT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Discount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ALWAYS_ALLOW_COMMEMORATION_QUEST_COUNT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ALWAYS_FULL_RELIGIOUS_TOURISM</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ALWAYS_LOYAL_COASTAL_HOME_CONTINENT</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ANYONE_PLUNDER_FAVOR</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ANYONE_PLUNDER_TO_FAVOR</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ANYONE_TRADE_TO_FAVOR</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_BAN_CHOP</td>
	<td rowspan="1">PLAYERS</td>
	<td>NoRemove</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_BAN_CITY_PRODUCTION</td>
	<td rowspan="1">PLAYERS</td>
	<td>BanDistrictBuildings</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_BAN_POLICY</td>
	<td rowspan="1">PLAYERS</td>
	<td>PolicyType</td>
	<td>String</td>
	<td>[Policies.PolicyType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_BAN_RESOURCE</td>
	<td rowspan="1">PLAYERS</td>
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_BAN_UNIT_PRODUCTION_YIELD</td>
	<td rowspan="2">PLAYERS</td>
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_BID_COST_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_BLOCK_UNIT_ENTRY</td>
	<td rowspan="1">PLAYERS</td>
	<td>UnitType</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_BUFF_UNIT_PRODUCTION_YIELD</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_BUILDING_FAVOR</td>
	<td rowspan="2">PLAYERS</td>
	<td>BuildingType</td>
	<td>String</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Favor</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_CAPITAL</td>
	<td rowspan="1">PLAYERS</td>
	<td>ProjectType</td>
	<td>String</td>
	<td>[Projects.ProjectType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_AUTO_THEMED_BUILDING</td>
	<td rowspan="1">PLAYERS</td>
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_CITY_TILES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_CULTURAL_IDENTITY_PRESSURE_RADIUS_FROM_CAPITAL</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_PLAYER_DIPLOMATIC_VICTORY_POINTS</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Tooltip</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>VictoryResolution</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_DISTRICT_AIR_SLOTS</td>
	<td rowspan="1">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_DISTRICT_AND_BUILDINGS_CREATE_UNIT_WITH_ABILITY_BY_CLASS</td>
	<td rowspan="1">PLAYERS</td>
	<td>UnitAbilityType</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_DISTRICT_CREATE_UNIT</td>
	<td rowspan="2">PLAYERS</td>
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_ADJUST_PLAYER_DISTRICT_CREATE_YIELD</td>
	<td rowspan="6">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="Argument">
	<td>MustReplaceImprovement</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldBasedOnAppeal</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_EMBARKED_UNIT_MOVEMENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_EMERGENCY_FAVOR_MODIFIER</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Member</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ENFORCE_BORDERS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_AERODROME_BUILDING_CONSTRUCTED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_ARMY_KILLED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_ARTIFACT_EXTRACTED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_CITY_RELIGION_CONVERSION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_CIVIC_BOOST</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_CONTINENT_DISCOVERED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_CORPS_KILLED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_CULTURE_BUILDING_CONSTRUCTED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_DISTRICT_CONSTRUCTED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_GREAT_PERSON_EARNED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_INDUSTRIAL_BUILDING_CONSTRUCTED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_NATURAL_WONDER_DISCOVERED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_NON_BARBARIAN_UNIT_KILLED_BY_GDR</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_NON_BARBARIAN_UNIT_SEA_KILLED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_PRIDE_MOMENT</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinScore</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_SCIENCE_BUILDING_CONSTRUCTED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_SPY_SUCCESSFUL_MISSION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_TECH_BOOST</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ERA_SCORE_PER_TRADE_ROUTE_COMPLETED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_EXTRA_FAVOR_PER_TURN</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_FAITH_FROM_DISPERSAL</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_FAITH_PEACEFUL_FOUNDERS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_PLAYER_FAVOR_REFUND_FOR_SUCCESSFUL_RESOLUTION</td>
	<td rowspan="3">PLAYERS</td>
	<td>Percent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>ResolutionType</td>
	<td>String</td>
	<td>[Resolutions.ResolutionType]</td>
</tr>
<tr class="Argument">
	<td>WhichEffect</td>
	<td>Integer</td>
	<td>1<br>2</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_FEAUTE_REQUIRED_FOR_SPECIALTY_DISTRICTS</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_FREE_BUILDING_WHEN_SPECIALTY_DISTRICT_CONSTRUCTED</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_FREE_BUILDING_WHEN_SPECIALTY_DISTRICT_CONSTRUCTED_EXCEPT</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_FREE_GREAT_PERSON_POINTS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_FREE_RESOURCE_IMPORT</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_FREE_RESOURCE_IMPORT_EXTRACTION</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_GOVERNMENT_SLOT_TYPE</td>
	<td rowspan="1">PLAYERS</td>
	<td>GovernmentSlotType</td>
	<td>String</td>
	<td>[GovernmentSlots.GovernmentSlotType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_GOVERNMENT_SLOT_TYPE_GRANT_FAVOR</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>GovernmentSlotType</td>
	<td>String</td>
	<td>[GovernmentSlots.GovernmentSlotType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_PLAYER_GOVERNOR_FAVOR</td>
	<td rowspan="3">PLAYERS</td>
	<td>FavorAmount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>GovernorType</td>
	<td>String</td>
	<td>[Governors.GovernorType]</td>
</tr>
<tr class="Argument">
	<td>Neutralize</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_GOVERNOR_POINTS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Delta</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_GREATPERSON_FAVOR_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_GRIEVANCE_DECAY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_GRIEVANCE_GENERATION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_HEALING_FROM_DISPERSAL</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_HAPPINESS</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_IDENTITY_PER_TURN_FOR_DOMESTIC_TRADE_ROUTE_ORIGIN</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_IMMEDIATE_TRADING_POST</td>
	<td rowspan="1">PLAYERS</td>
	<td>ImmediateTradingPost</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_IMPROVED_ROUTE_LEVEL</td>
	<td rowspan="1">PLAYERS</td>
	<td>ImprovedRouteLevel</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_INTERNATIONAL_TRADE_ROUTE_YIELD_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_JOINTWAR_EXPERIENCE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Range</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_JOINTWAR_PLUNDER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Multiplier</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_LEVIED_UNIT_UPGRADE_DISCOUNT_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_LEVY_DISCOUNT_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Percent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_LOYALTY_MARTIAL_LAW_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_MAX_DISTRICTS</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_MAX_TRADE_ROUTES</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_MAX_WARMONGER_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>MaxPercent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_NO_CAP_RESOURCE</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_NO_OCCUPATION_PENALTIES</td>
	<td rowspan="1">CITIES</td>
	<td>NoPenalties</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_OPEN_BORDERS_FROM_INFLUENCE</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_OTHER_GOVERNMENT_INTOLERANCE</td>
	<td rowspan="2">PLAYERS</td>
	<td>IntoleranceMultiplier</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>SameEraIntoleranceFlatBonus</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_POST_COMBAT_LOYALTY</td>
	<td rowspan="2">PLAYERS</td>
	<td>AffectLocal</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_POST_PILLAGE_LOYALTY</td>
	<td rowspan="2">PLAYERS</td>
	<td>AffectLocal</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_PROGRESS_DIFF_TRADE_BONUS</td>
	<td rowspan="1">PLAYERS</td>
	<td>TechCivicsPerYield</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_PROPERTY</td>
	<td rowspan="1">PLAYERS</td>
	<td>PropertyName</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_OVERALL_TOURISM_REDUCTION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Modifier</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_POLICY_FAVOR</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>PolicyType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_PREVENT_HARVEST_RESOURCE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_RANDOM_CIVIC_BOOST_GOODY_HUT</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Source</td>
	<td>String</td>
	<td>CAPTURED_CITY</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_RANDOM_EVENT_AVOID</td>
	<td rowspan="1">PLAYERS</td>
	<td>RandomEventType</td>
	<td>String</td>
	<td>[RandomEvents.RandomEventType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_RANDOM_TECHNOLOGY_BOOST_GOODY_HUT</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Source</td>
	<td>String</td>
	<td>CAPTURED_CITY</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_RELIGIOUS_TOURISM_REDUCTION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Modifier</td>
	<td>Integer</td>
	<td>[Modifiers.ModifierId]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_RESOURCE_ACCUMULATION_MODIFIER</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_RESOURCE_STOCKPILE_CAP</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_ROCK_BAND_UNIT_ALBUM_SALES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SCIENCE_VICTORY_POINTS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SCIENCE_VICTORY_POINTS_PER_TURN</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="2">❔</td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_SEND_INFLUENCE_TOKEN_FAVOR_BY_BONUS_TYPE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>BonusType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="2">❔</td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_SEND_TRADE_ROUTE_FAVOR_BY_BONUS_TYPE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>BonusType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SKIP_FREE_CITY_STEP</td>
	<td rowspan="1">PLAYERS</td>
	<td>Skip</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SPECIALTY_DISTRICT_CANNOT_BE_BUILT_ADJACENT_TO_CITY</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SPECIFIC_DISTRICT_GRANT_ENVOYS</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_SPY_BONUS</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Offense</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_STEAL_TECH_BOOSTS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_STRENGTH_MODIFIER</td>
	<td rowspan="1">COMBATS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SUZERAIN_BONUS_DISABLED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Disable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SUZERAIN_FAVOR_BY_BONUS_TYPE</td>
	<td rowspan="1">PLAYERS</td>
	<td>BonusType</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_SUZERAIN_FAVOR_MULTIPLIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_TERRAIN_WORK_IMPASSABLE_MODIFIER</td>
	<td rowspan="2">PLAYERS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_TOKEN_ON_FIRST_MEETING</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_TOURISM</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_TOURISM_FAVOR</td>
	<td rowspan="2">PLAYERS</td>
	<td>Favor</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Tourism</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_TOURISM_FROM_NATIONAL_PARKS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_TRADE_GAIN_TILES_EN_ROUTE</td>
	<td rowspan="1">PLAYERS</td>
	<td>GainTileRadius</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_BY_CITY_STATE_BONUS_TYPE_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_CAPACITY_ON_MEETING</td>
	<td rowspan="1">PLAYERS</td>
	<td>Intercontinental</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_DESTINATION_YIELD_FOR_ALLY_ROUTE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_ORIGIN_YIELD_FOR_ALLY_ROUTE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_RELIGIOUS_PRESSURE</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Destination</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Origin</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_TOURISM_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_YIELD_MODIFIER</td>
	<td rowspan="4">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>Destination</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Origin</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_YIELD_PER_IMPROVEMENT_IN_TARGET_CITY</td>
	<td rowspan="6">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>Destination</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Domestic</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="Argument">
	<td>Origin</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_YIELD_PER_PATH_TILE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_YIELD_PER_POST_IN_FOREIGN_CITY</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_YIELD_PER_POST_IN_OWN_CITY</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_YIELD_PER_TERRAIN_FOR_DOMESTIC</td>
	<td rowspan="5">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>Destination</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Origin</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_PLAYER_TRADE_ROUTE_YIELD_PER_TERRAIN_FOR_INTERNATIONAL</td>
	<td rowspan="4">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>Origin</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_UNIT_BUILD_DISABLED</td>
	<td rowspan="1">PLAYERS</td>
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_UNIT_DISTRICT_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_UNIT_PROJECT_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_UNIT_UPGRADE_DISCOUNT_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_UNIT_UPGRADE_RESOURCE_COST_DISCOUNT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_UNIT_WONDER_PERCENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_VALID_IMPROVEMENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_VALID_UNIT_BUILD</td>
	<td rowspan="1">PLAYERS</td>
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_WARMONGER_MULTIPLIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_WMD_COUNT</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Type</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLAYER_WMD_MAINTENANCE_MODIFIER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_YIELD_CHANGE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_YIELD_CHANGE_PER_TRIBUTARY</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_YIELD_CHANGE_PER_USED_INFLUENCE_TOKEN</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_YIELD_MODIFIER_PER_EARNED_GREAT_PERSON</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLAYER_YIELD_MODIFIER_PER_TRIBUTARY</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PLOT_PURCHASE_COST</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLOT_PURCHASE_COST_TERRAIN</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PLOT_YIELD</td>
	<td rowspan="2">PLOTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_POLICY_AMENITY</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_POLICY_HOUSING</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_POPULATION_AFTER_CONQUEST</td>
	<td rowspan="1">CITIES</td>
	<td>Percent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_PREVENT_STRUCTURAL_DAMAGE</td>
	<td rowspan="1">CITIES</td>
	<td>Prevent</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_PROJECT_PRODUCTION</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ProjectType</td>
	<td>String</td>
	<td>[Projects.ProjectType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_RANDOM_EVENT_MODIFIED_DAMAGE_OPPOSING_PLAYER</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>RandomEventType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_RANDOM_EVENT_NO_UNIT_DAMAGE</td>
	<td rowspan="2">PLAYERS</td>
	<td>NoDamage</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>RandomEventType</td>
	<td>String</td>
	<td>[RandomEvents.RandomEventType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_RELIGION_AMENITIES_FOR_MINIMUM_FOLLOWERS</td>
	<td rowspan="2">CITIES</td>
	<td>Amenities</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Followers</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RELIGION_ANYONE_CONDEMNS_FAVOR</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RELIGION_BUILDING_DISCOUNT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Discount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RELIGIOUS_COMBAT_LOSS</td>
	<td rowspan="1">PLAYERS</td>
	<td>ReductionPercent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RELIGION_CONDEMN_PROHIBITED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Prohibited</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RELIGIOUS_SPREAD_DISTANCE</td>
	<td rowspan="1">PLAYERS</td>
	<td>DistanceChange</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_RELIGIOUS_SPREAD_STRENGTH</td>
	<td rowspan="3">PLAYERS</td>
	<td>EnhancingTechType</td>
	<td>String</td>
	<td>[Technologies.TechnologyType]</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>SpreadMultiplier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TechEnabledSpreadMultiplier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RESOURCE_POWER_PROVIDED_GOVERNOR</td>
	<td rowspan="1">GOVERNORS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="4">❔</td>
	<td rowspan="4">EFFECT_ADJUST_RESOURCE_YIELD_BY_COUNT</td>
	<td rowspan="4">GOVERNORS</td>
	<td>ResourceType</td>
	<td>String</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>MinimumCount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RIVER_DISTRICT_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_RIVER_WONDER_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_SPACE_RACE_PROJECTS_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_TERRAIN_YIELD_FROM_ADJACENT_IMPROVEMENTS</td>
	<td rowspan="4"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td>[Terrains.TerrainType]</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_TECHNOLOGY_BOOST</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_TRADE_ROUTE_CAPACITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_TRADE_ROUTE_YIELD</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_TRADE_ROUTE_YIELD_CHANGE</td>
	<td rowspan="4">TRADE ROUTES</td>
	<td>AffectDestination</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>AffectOrigin</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_TRADE_ROUTE_YIELD_FOR_DOMESTIC</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Intercontinental</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_TRADE_ROUTE_YIELD_FOR_INTERNATIONAL</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Intercontinental</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_TRADE_ROUTE_YIELD_FOR_OTHERS</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_TRADE_ROUTE_YIELD_FROM_OTHERS</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Domestic</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_TRADE_ROUTE_YIELD_PER_SPECIALTY_DISTRICT_FOR_DOMESTIC</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_TRADE_ROUTE_YIELD_PER_SPECIALTY_DISTRICT_FOR_INTERNATIONAL</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_TRADE_ROUTE_YIELD_TO_OTHERS</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Domestic</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_TRAIT_AMENITY</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ADVANCED_COASTAL_RAID</td>
	<td rowspan="1">UNITS</td>
	<td>UseAdvancedCoastalRaid</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ADVANCED_PILLAGING</td>
	<td rowspan="1">UNITS</td>
	<td>UseAdvancedPillaging</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_AGAINST_DISTRICT_COMBAT_BONUS</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ANTI_AIR_STRENGTH</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ATTACK_AND_MOVE</td>
	<td rowspan="1">UNITS</td>
	<td>CanMove</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ATTACK_EXPERIENCE_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ATTACK_RANGE</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_BARBARIAN_COMBAT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_BOOST_ALL_SPIES</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Defense</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_BUILD_CHARGES</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_BYPASS_COMBAT_UNIT</td>
	<td rowspan="1">UNITS</td>
	<td>Bypass</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_BYPASS_WALLS</td>
	<td rowspan="1">UNITS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_BYPASS_WALLS_PROMOTION_CLASS</td>
	<td rowspan="1">UNITS</td>
	<td>PromotionClass</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_CANNOT_ATTACK</td>
	<td rowspan="1">UNITS</td>
	<td>Disable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_CLEAR_TERRAIN_START_MOVEMENT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_COMBAT_CAPTURE</td>
	<td rowspan="2">UNITS</td>
	<td>CanCapture</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_COMBAT_STRENGTH</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td>[Units.UnitType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_COMBAT_UNIT_CAPTURE</td>
	<td rowspan="2">UNITS</td>
	<td>CanCapture</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_CONVERTS_BARBARIANS</td>
	<td rowspan="1">UNITS</td>
	<td>Converts</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_DAMAGE</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_DEFENSE</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_DIPLO_VISIBILITY_COMBAT_MODIFIER</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>DeltaWithOpponent</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_DISASTER_CHARGES</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_DOMAIN_PRODUCTION</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Domain</td>
	<td>String</td>
	<td>DOMAIN_AIR<br>DOMAIN_LAND<br>DOMAIN_SEA</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENABLE_WALL_ATTACK</td>
	<td rowspan="1">UNITS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENABLE_WALL_ATTACK_WHOLE_GAME</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENABLE_WALL_ATTACK_WHOLE_GAME_SAME_RELIGION</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENABLE_WALL_ATTACK_PROMOTION_CLASS</td>
	<td rowspan="1">UNITS</td>
	<td>PromotionClass</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENABLE_WALL_ATTACK_WHOLE_GAME_PROMOTION_CLASS</td>
	<td rowspan="1">UNITS</td>
	<td>PromotionClass</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENEMY_HEAL</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENEMY_TERRITORY_START_MOVEMENT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ENTER_FOREIGN_LANDS</td>
	<td rowspan="1">UNITS</td>
	<td>Enter</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ESCAPE_BOOST</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ESCORT_MOBILITY</td>
	<td rowspan="1">UNITS</td>
	<td>EscortMobility</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_EVICT_PERCENT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_EXERT_ZOC</td>
	<td rowspan="1">UNITS</td>
	<td>Exert</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_EXPERIENCE_LEVEL</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_EXPERIENCE_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_EXTRACT_SEA_ARTIFACTS</td>
	<td rowspan="1">UNITS</td>
	<td>Extract</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FAITH_ON_DISTRICT_PLUNDER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FAITH_ON_IMPROVEMENT_PLUNDER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FIGHT_WHILE_EMBARKED</td>
	<td rowspan="1">UNITS</td>
	<td>CanFight</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FLANKING_BONUS_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Percent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FORCE_RETREAT</td>
	<td rowspan="1">UNITS</td>
	<td>ForceRetreat</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FOREIGN_SPREAD_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FRIENDLY_HEAL</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FRIENDLY_TERRITORY_COMBAT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_FRIENDLY_TERRITORY_START_MOVEMENT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_GRANT_EXPERIENCE</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_GREAT_PERSON_CHARGES</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_HEAL</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_HEALING_MODIFIERS</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Type</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_HEALING_RELIGION_MODIFIERS</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>Type</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_HIDDEN_VISIBILITY</td>
	<td rowspan="1">UNITS</td>
	<td>Hidden</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_HOLY_CITIES_COMBAT_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_CLIFF_WALLS</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_RANGED_VS_DISTRICT_PENALTY</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_RESOURCE_MAINTENANCE</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_RIVERS</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_SHORES</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_SHORESFORESTHILLS</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_STRATEGIC_RESOURCE_LEVIED</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_IGNORE_TERRAIN_COST</td>
	<td rowspan="2">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Type</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_IGNORE_ZOC</td>
	<td rowspan="1">UNITS</td>
	<td>Ignore</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_INITIATION_YIELD</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_INITIATION_YIELD_POPULATION</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_JUMP_ABILITY</td>
	<td rowspan="1">UNITS</td>
	<td>Range</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_LAND_VICTORY_SPREAD</td>
	<td rowspan="1">UNITS</td>
	<td>LandVictorySpread</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_MAINTENANCE_DISCOUNT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_MILITARY_FORMATION</td>
	<td rowspan="1">UNITS</td>
	<td>MilitaryFormationType</td>
	<td>String</td>
	<td>ARMY_MILITARY_FORMATION<br>CORPS_MILITARY_FORMATION</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_MOVE_AND_ATTACK</td>
	<td rowspan="1">UNITS</td>
	<td>CanAttack</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_MOVEMENT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_NATURAL_WONDER_DEFERRED_CHARGES</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_NEUTRAL_HEAL</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_NEIGHBOR_COMBAT_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_NO_FOREIGN_SPREAD</td>
	<td rowspan="1">UNITS</td>
	<td>NoSpread</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_NO_MOVE_TERRAIN</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_NO_REDUCTION_DAMAGE</td>
	<td rowspan="1">UNITS</td>
	<td>NoReduction</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_NUM_ATTACKS</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_OWNER</td>
	<td rowspan="1">UNITS</td>
	<td>NewOwner</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_PARADROP_ABILITY</td>
	<td rowspan="1">UNITS</td>
	<td>CanDrop</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_PER_LUXURY_ATTACK_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_PER_UNUSED_MOVEMENT_COMBAT_BONUS</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_PILLAGE_DISTRICT_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_PILLAGE_IMPROVEMENT_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_PLUNDER_YIELDS</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_POST_COMBAT_HEAL</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_UNIT_POST_COMBAT_YIELD</td>
	<td rowspan="4">UNITS</td>
	<td>OnlyWhenDefeatedEarlierEraUnit</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>PercentDefeatedStrength</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReligiousCombat</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_POST_TOURISM_BOMB_LOYALTY</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_PRODUCTION</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_PROMOTE_NO_FINISH_MOVES</td>
	<td rowspan="1">UNITS</td>
	<td>NoFinishMoves</td>
	<td>Boolean</td>
	<td>[Units.UnitType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_PROPERTY</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_PURCHASE_COST</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_RAIDING</td>
	<td rowspan="2">UNITS</td>
	<td>Bonus</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>CanRaid</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_RELIC_UPON_DEATH</td>
	<td rowspan="1">UNITS</td>
	<td>RelicUponDeath</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_ROCK_BAND_LEVEL_DISTRICT</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_ROCK_BAND_LEVEL_IMPROVEMENT</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ROCK_BAND_LEVEL_NATIONAL_PARK</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ROCK_BAND_LEVEL_NATURAL_WONDER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_ROCK_BAND_TOURISM_BOMB_VALUE_PEACE</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SEA_MOVEMENT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SEE_HIDDEN</td>
	<td rowspan="1">UNITS</td>
	<td>SeeHidden</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SEE_THROUGH_FEATURES</td>
	<td rowspan="1">UNITS</td>
	<td>CanSee</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SEE_THROUGH_TERRAIN</td>
	<td rowspan="1">UNITS</td>
	<td>CanSee</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SIGHT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SPREAD_CHARGES</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SPY_COUNTERSPY_ADJACENT_LEVEL_BOOST</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SPY_COUNTERSPY_ENTIRE_CITY</td>
	<td rowspan="1">UNITS</td>
	<td>EntireCity</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SPY_ESTABLISH_TIME</td>
	<td rowspan="1">UNITS</td>
	<td>ReductionPercent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_SPY_OFFENSIVE_OPERATION_TIME</td>
	<td rowspan="1">UNITS</td>
	<td>ReductionPercent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_UNIT_SPY_OPERATION_CHANCE</td>
	<td rowspan="3">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Offensive</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>OperationType</td>
	<td>String</td>
	<td>[UnitOperations.OperationType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_SPY_OPERATION_TIME</td>
	<td rowspan="2">UNITS</td>
	<td>OperationType</td>
	<td>String</td>
	<td>[UnitOperations.OperationType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>ReductionPercent</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_STRENGTH_FROM_CITY_CULTURAL_IDENTITY</td>
	<td rowspan="1">COMBATS</td>
	<td>ThresholdPercent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_STRENGTH_REDUCTION_FOR_DAMAGE_MODIFIER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_SUPPORT_BONUS_MODIFIER</td>
	<td rowspan="2">UNITS</td>
	<td>Percent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>DomainType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ADJUST_UNIT_TAG_ERA_PRODUCTION</td>
	<td rowspan="3">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>EraType</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="Argument">
	<td>UnitPromotionClass</td>
	<td>String</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_TOURISM_BOMB_CONVERT_CITY</td>
	<td rowspan="1">UNITS</td>
	<td>Convert</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_TOURISM_BOMB_DISTRICT</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_TOURISM_BOMB_IMPROVEMENT</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_TOURISM_BOMB_NATIONAL_PARK</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_TOURISM_BOMB_NATURAL_WONDER</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_TOURISM_BOMB_RANGE</td>
	<td rowspan="2">UNITS</td>
	<td>Modifier</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Range</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_TRADE_ROUTE_PLUNDER_IMMUNITY</td>
	<td rowspan="1">UNITS</td>
	<td>DomainType</td>
	<td>String</td>
	<td>DOMAIN_AIR<br>DOMAIN_LAND<br>DOMAIN_SEA</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNIT_UPGRADE_GOODY_HUT</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_VALID_TERRAIN</td>
	<td rowspan="2">UNITS</td>
	<td>TerrainType</td>
	<td>String</td>
	<td>[Terrains.TerrainType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Valid</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_WATER_DAMAGE_PROTECTION</td>
	<td rowspan="2">UNITS</td>
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>WaterDamage</td>
	<td>Integer</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_WMD_PROTECTION</td>
	<td rowspan="2">UNITS</td>
	<td>Blast</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Fallout</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_UNIT_YIELD_PER_TOURISM_BOMB</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_UNITS_RELIGIOUS_STRENGTH_BY_RELIGION_TYPE</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_VALID_FEATURES_DISTRICTS</td>
	<td rowspan="2">CITIES</td>
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>FeatureType</td>
	<td>String</td>
	<td>[Features.FeatureType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_VALID_FEATURES_WONDERS</td>
	<td rowspan="1">CITIES</td>
	<td>FeatureType</td>
	<td>String</td>
	<td>[Features.FeatureType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_WAR_WEARINESS</td>
	<td rowspan="4">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>Domestic</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Enemy</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>Overall</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_WATER_HOUSING</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_WONDER_ADJACENT_NATURAL_WONDER_PRODUCTION</td>
	<td rowspan="2"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>FeatureType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_ADJUST_WONDER_ERA_PRODUCTION</td>
	<td rowspan="4">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>EndEra</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>IsWonder</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StartEra</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADJUST_WONDER_PRODUCTION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ADJUST_WONDER_YIELD_CHANGE</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ADOPT_ALLY_FOUNDED_RELIGIONS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Adopt</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_CULTURE_SHARING</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_ENVOY_POINTS_FROM_ALLY_TRIBUTARIES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_GRANT_SHARED_VIS</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_PRESSURE_FROM_NO_ALLY_RELIGION</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_RESEARCH_AGREEMENT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_SCIENCE_SHARING</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_SHARE_SUZERAIN</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ALLIANCE_TOURISM_SHARING</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_ALLIANCE_YIELD_INCOME_FROM_ALLY_RELIGION</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ASSIGN_CITY_PROPERTY</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ASSIGN_DISTRICT_PROPERTY</td>
	<td rowspan="1">DISTRICTS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ASSIGN_GAME_PROPERTY</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ASSIGN_PLAYER_PROPERTY</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ASSIGN_UNIT_PROPERTY</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ATTACH_MODIFIER</td>
	<td rowspan="1">ANY</td>
	<td>ModifierId</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_ATTACH_MODIFIER_IF_PROMOTION_CLASS_MATCHES</td>
	<td rowspan="3">UNITS</td>
	<td>ModifierId</td>
	<td>String</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>UnitPromotionClassType</td>
	<td>String</td>
	<td>[UnitPromotionClasses.UnitPromotionClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ATTACH_MODIFIER_TO_MINORCIVBONUSTYPE</td>
	<td rowspan="1">ANY</td>
	<td>ModifierId</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ATTACH_MODIFIER_TO_PLAYERTYPE</td>
	<td rowspan="1">ANY</td>
	<td>ModifierId</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ATTACH_UNIT_MODIFIER</td>
	<td rowspan="1">COMBATS</td>
	<td>ModifierId</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_CHANGE_UNIT_OPERATION_AVAILABILITY</td>
	<td rowspan="2">UNITS</td>
	<td>Available</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>OperationType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_CITY_RECOMMISSION_REACTOR</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_AGENDA_ANGEVIN_EMPIRE</td>
	<td rowspan="5">PLAYERS</td>
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>HighPopulationThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>LowPopulationThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="8"></td>
	<td rowspan="8">EFFECT_DIPLOMACY_AGENDA_ARCHIPELAGIC_STATE</td>
	<td rowspan="8">PLAYERS</td>
	<td>AcceptableIslandPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="8"></td>
	<td rowspan="8">✓</td>
	<td rowspan="8">✓</td>
	<td rowspan="8">✓</td>
	<td rowspan="8"></td>
</tr>
<tr class="Argument">
	<td>MaxNegativeModifier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxPositiveModifier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxTilesLargeIsland</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxTilesMediumIsland</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxTilesSmallIsland</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_AGENDA_AYYUBID_DYNASTY</td>
	<td rowspan="1">PLAYERS</td>
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_AGENDA_BLACK_QUEEN</td>
	<td rowspan="1">PLAYERS</td>
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_AGENDA_BULL_MOOSE</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_AGENDA_BUSHIDO</td>
	<td rowspan="1">PLAYERS</td>
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_AGENDA_CANADIAN_EXPEDITIONARY</td>
	<td rowspan="5">PLAYERS</td>
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="7"></td>
	<td rowspan="7">EFFECT_DIPLOMACY_AGENDA_END_TO_SUFFERING</td>
	<td rowspan="7">PLAYERS</td>
	<td>DisappointingHolySitePercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="7"></td>
	<td rowspan="7">✓</td>
	<td rowspan="7">✓</td>
	<td rowspan="7">✓</td>
	<td rowspan="7"></td>
</tr>
<tr class="Argument">
	<td>DisappointingLargeCityPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxNegativeModifier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxPositiveModifier</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TargetHolySitePercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TargetLargeCityPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="12"></td>
	<td rowspan="12">EFFECT_DIPLOMACY_AGENDA_ENVIRONMENT</td>
	<td rowspan="12">PLAYERS</td>
	<td>ForestPlacedValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="12"></td>
	<td rowspan="12">✓</td>
	<td rowspan="12">✓</td>
	<td rowspan="12">✓</td>
	<td rowspan="12">✓</td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>HighThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>LowThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxDiploModifierMagnitude</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>NationalParkConstructionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>PlotFeatureRemovedValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ScoreAllowancePerEra</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="13"></td>
	<td rowspan="13">EFFECT_DIPLOMACY_AGENDA_EXPLOITATIVE</td>
	<td rowspan="13">PLAYERS</td>
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="13"></td>
	<td rowspan="13">✓</td>
	<td rowspan="13">✓</td>
	<td rowspan="13">✓</td>
	<td rowspan="13"></td>
</tr>
<tr class="Argument">
	<td>HighScoreThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>LowScoreThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxDiploModifierMagnitude</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>NationalParkConstructionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>PlotFeatureRemovalValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TileImprovementHighThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TileImprovementLowThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TileImprovementPreferenceValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="7"></td>
	<td rowspan="7">EFFECT_DIPLOMACY_AGENDA_FLAT_EARTHER</td>
	<td rowspan="7">PLAYERS</td>
	<td>DiploModForCircumnavigation</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="7"></td>
	<td rowspan="7"></td>
	<td rowspan="7"></td>
	<td rowspan="7">✓</td>
	<td rowspan="7"></td>
</tr>
<tr class="Argument">
	<td>DiploModPerSpaceProject</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>DiploModPerSpaceport</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="7"></td>
	<td rowspan="7">EFFECT_DIPLOMACY_AGENDA_HORN_CHEST_LOINS</td>
	<td rowspan="7">PLAYERS</td>
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="7"></td>
	<td rowspan="7"></td>
	<td rowspan="7">✓</td>
	<td rowspan="7">✓</td>
	<td rowspan="7"></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>CantBuildDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>CorpsPrereqCivic</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="7"></td>
	<td rowspan="7">EFFECT_DIPLOMACY_AGENDA_HORSE_LORD</td>
	<td rowspan="7">PLAYERS</td>
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="7"></td>
	<td rowspan="7"></td>
	<td rowspan="7">✓</td>
	<td rowspan="7">✓</td>
	<td rowspan="7"></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>PromotionClass1</td>
	<td>String</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
</tr>
<tr class="Argument">
	<td>PromotionClass2</td>
	<td>String</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_AGENDA_KAITIAKITANGA</td>
	<td rowspan="6">PLAYERS</td>
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_AGENDA_LAST_VIKING_KING</td>
	<td rowspan="5">PLAYERS</td>
	<td>BetterMilitaryBonus</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopMilitaryBonus</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_AGENDA_LAWGIVER</td>
	<td rowspan="6">PLAYERS</td>
	<td>BonusIfNotOriginalOwner</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_AGENDA_LORD_OF_MINES</td>
	<td rowspan="6">PLAYERS</td>
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_AGENDA_OPPORTUNIST</td>
	<td rowspan="5">PLAYERS</td>
	<td>EachSurpriseWarBonus</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>NeverSurpriseWarPenalty</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>RecentSurpriseWarBonus</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SurpriseWarDegradeTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_AGENDA_OPTIMUS_PRINCEPS</td>
	<td rowspan="5">PLAYERS</td>
	<td>BetterTerritoryBonus</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopTerritoryBonus</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_DIPLOMACY_AGENDA_PARANOID</td>
	<td rowspan="2">PLAYERS</td>
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_AGENDA_PATRON_OF_ARTS</td>
	<td rowspan="5">PLAYERS</td>
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_DIPLOMACY_AGENDA_PERPETUALLY_ON_GUARD</td>
	<td rowspan="3">PLAYERS</td>
	<td>PenaltyPerOccupiedCity</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_AGENDA_QUEEN_OF_NILE</td>
	<td rowspan="1">PLAYERS</td>
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_AGENDA_RAVEN_BANNER</td>
	<td rowspan="5">PLAYERS</td>
	<td>BottomPercentage</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopPercentage</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_AGENDA_SHORT_LIFE_GLORY</td>
	<td rowspan="6">PLAYERS</td>
	<td>EachWarDeclaredBonus</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>MajorWarBonus</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxWarDeclaredBonus</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>NotAtWarPenalty</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SinceWarPenaltyTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_AGENDA_SIMON_BOLIVAR</td>
	<td rowspan="6">PLAYERS</td>
	<td>MinPromotedUnits</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
</tr>
<tr class="Argument">
	<td>NumSteps</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>PercentageDifferencePerStep</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ScorePerStep</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_DIPLOMACY_AGENDA_TURTLER</td>
	<td rowspan="4">PLAYERS</td>
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="13"></td>
	<td rowspan="13">EFFECT_DIPLOMACY_AGENDA_WITH_SHIELD_OR_ON_IT</td>
	<td rowspan="13">PLAYERS</td>
	<td>AvoidedWarPenalty</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="13"></td>
	<td rowspan="13">✓</td>
	<td rowspan="13">✓</td>
	<td rowspan="13">✓</td>
	<td rowspan="13"></td>
</tr>
<tr class="Argument">
	<td>AvoidedWarPenaltyTurnsToRampUp</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>HighThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>LowThreshold</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxDiploModifierMagnitude</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>PaidForPeacePenalty</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>PaidForPeacePenaltyTurnsToFadeOut</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_DIPLOMACY_AGENDA_ZEALOT</td>
	<td rowspan="4">PLAYERS</td>
	<td>BottomRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TopRankingDiploMod</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_ARCHAEOLOGY</td>
	<td rowspan="6">PLAYERS</td>
	<td>DiplomacyKey</td>
	<td>String</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MessageThrottle</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ModifierPerTransgression</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_BROKEN_PLEDGE</td>
	<td rowspan="5">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>ModifierPerTransgression</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_BROKEN_PROMISE</td>
	<td rowspan="5">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>ModifierPerTransgression</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_CONVERT_CITY</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_CULTURAL_ID</td>
	<td rowspan="5">PLAYERS</td>
	<td>CityGainLowerBound</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>CityGainUpperBound</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ScorePerCity</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="8"></td>
	<td rowspan="8">EFFECT_DIPLOMACY_ESPIONAGE</td>
	<td rowspan="8">PLAYERS</td>
	<td>DiplomacyKey</td>
	<td>String</td>
	<td></td>
	<td rowspan="8"></td>
	<td rowspan="8">✓</td>
	<td rowspan="8">✓</td>
	<td rowspan="8">✓</td>
	<td rowspan="8"></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MessageThrottle</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ModifierPerTransgression</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_DIPLOMACY_FORCE_INCURSION</td>
	<td rowspan="3">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_DIPLOMACY_GOVERNMENTS</td>
	<td rowspan="3">PLAYERS</td>
	<td>IncrementTurns</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_KEPT_PLEDGE</td>
	<td rowspan="6">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ModifierPerKeptPledge</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_KEPT_PROMISE</td>
	<td rowspan="6">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ModifierPerKeptPromise</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">EFFECT_DIPLOMACY_NEW_WARMONGER</td>
	<td rowspan="4">PLAYERS</td>
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>LowerLimit</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>PercentOfGrievances</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_NO_PLEDGE</td>
	<td rowspan="5">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>ModifierPerTransgression</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_NO_PROMISE</td>
	<td rowspan="5">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>ModifierPerTransgression</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DIPLOMACY_ONE_SIDED_TRADES</td>
	<td rowspan="5">PLAYERS</td>
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>MaxValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TradeValuePerModifierPoint</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_DIPLOMACY_RANDOM</td>
	<td rowspan="3">PLAYERS</td>
	<td>DifficultyOffset</td>
	<td>String</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="7"></td>
	<td rowspan="7">EFFECT_DIPLOMACY_SETTLED_CITIES</td>
	<td rowspan="7">PLAYERS</td>
	<td>DiplomacyKey</td>
	<td>String</td>
	<td></td>
	<td rowspan="7"></td>
	<td rowspan="7">✓</td>
	<td rowspan="7">✓</td>
	<td rowspan="7">✓</td>
	<td rowspan="7"></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MessageThrottle</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="13"></td>
	<td rowspan="13">EFFECT_DIPLOMACY_SIMPLE_EFFECT</td>
	<td rowspan="13">PLAYERS</td>
	<td>Accumulates</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="13"></td>
	<td rowspan="13">✓</td>
	<td rowspan="13">✓</td>
	<td rowspan="13">✓</td>
	<td rowspan="13"></td>
</tr>
<tr class="Argument">
	<td>DiplomacyKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>HiddenAgenda</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>IncrementTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MessageThrottle</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>OnlyOwnersCity</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionTurns</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>ReductionValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_TENSION</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_THIRD_PARTY_EFFECTS</td>
	<td rowspan="6">PLAYERS</td>
	<td>AmountPerIncident</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>EffectType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>IncrementValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InitialValue</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>MaxEffectMagnitude</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_DIPLOMACY_THIRD_PARTY_WARMONGER</td>
	<td rowspan="2">PLAYERS</td>
	<td>LowerLimit</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>PercentOfGrievancesDelta</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_DIPLOMACY_TRADE_RELATIONS</td>
	<td rowspan="6">PLAYERS</td>
	<td>BonusPerRoute</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
</tr>
<tr class="Argument">
	<td>NoTradePenalty</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>OnlyInboundTrade</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>SimpleModifierDescription</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>StatementKey</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TradeBonus</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DISABLE_PLAYER_GRIEVANCE_DECAY</td>
	<td rowspan="1"></td>
	<td>Disable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DIPLOMACY_WARMONGER</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DISTRICT_ADD_NAVAL_UNIT</td>
	<td rowspan="1">PLAYERS</td>
	<td>DistrictType</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_DISTRICT_ADJACENCY</td>
	<td rowspan="5">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>Description</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>TilesRequired</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_DO_NOTHING</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ENABLE_BUILDING_FAITH_PURCHASE</td>
	<td rowspan="1">CITIES</td>
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ENABLE_RELIGION_AUTO_SPREAD</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ENABLE_RELIGION_AWARDS_ENVOY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ENABLE_RELIGION_AWARDS_ENVOY_RELIGIOUS_PRESSURE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_ENABLE_SPECIFIC_BUILDING_FAITH_PURCHASE</td>
	<td rowspan="1">CITIES</td>
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_ENABLE_UNIT_FAITH_PURCHASE</td>
	<td rowspan="1">CITIES</td>
	<td>Tag</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_EXPLORE_ENTIRE_MAP</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_FEATURE_ADJACENCY</td>
	<td rowspan="6">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>Description</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>FeatureType</td>
	<td>String</td>
	<td>[Features.FeatureType]</td>
</tr>
<tr class="Argument">
	<td>TilesRequired</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GOVERNOR_ADJUST_CITY_COPY_LUXURIES_FOR_IMPORT</td>
	<td rowspan="1">GOVERNORS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GOVERNOR_ADJUST_CITY_COPY_STRATEGICS_FOR_IMPORT</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GOVERNOR_ADJUST_CITY_TOKENS_GRANTED</td>
	<td rowspan="1">GOVERNORS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GOVERNOR_ADJUST_CITY_TOKENS_GRANTED_MODIFIER</td>
	<td rowspan="1">GOVERNORS</td>
	<td>Percent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GOVERNOR_ADJUST_IDENITITY_PER_TITLE</td>
	<td rowspan="1">GOVERNORS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_ABILITY</td>
	<td rowspan="2">UNITS</td>
	<td>AbilityType</td>
	<td>String</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>ModifierId</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_AIR_SLOTS</td>
	<td rowspan="1">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_ALL_TECHNOLOGY_BOOST_BY_ERA</td>
	<td rowspan="2">PLAYERS</td>
	<td>EndEraType</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>StartEraType</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_BOOST_WITH_GREAT_PERSON</td>
	<td rowspan="3">PLAYERS</td>
	<td>GreatPersonClass</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>OtherPlayers</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>TechBoost</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_GRANT_BUILDING_IN_CAPITAL</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_GRANT_BUILDING_IN_CITY</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_BUILDING_IN_CITY_IGNORE</td>
	<td rowspan="1">CITIES</td>
	<td>BuildingType</td>
	<td>String</td>
	<td>[Buildings.BuildingType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_CHEAPEST_BUILDING_IN_CITY</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_CITY_LOYALTY</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_CITY_OWNER_INFLUENCE_TOKEN_WONDER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_CITY_ROAD_TO_CAPITAL</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_CITY_TRADING_POST</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_CITY_YIELD_PERCENT_BUILDING_CREATED_COST</td>
	<td rowspan="3">CITIES</td>
	<td>BuildingProductionPercent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>IncludeWonder</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_CITY_YIELD_PERCENT_UNIT_CREATED_COST</td>
	<td rowspan="2">CITIES</td>
	<td>UnitProductionPercent</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_COMBAT_ADJACENCY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Enable</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_FOUND_FOREIGN_CITY_TRADE_ROUTE_CAPACITY</td>
	<td rowspan="1"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_FREE_RESOURCE_FROM_UNIT_PLOT</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_FREE_RESOURCE_EXTRACTED</td>
	<td rowspan="2"></td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_FREE_RESOURCE_IN_CITY</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_FREE_RESOURCE_VISIBILITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>ResourceType</td>
	<td>String</td>
	<td>[Resources.ResourceType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_GREAT_PERSON_CLASS_IN_CITY</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>GreatPersonClassType</td>
	<td>String</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_HEAL_AFTER_ACTION</td>
	<td rowspan="1">UNITS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_INFLUENCE_TOKEN</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_INFLUENCE_TOKEN_LEVY_MILITARY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_GOLDEN_AGE_TRADE_ROUTE_CAPACITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLAYER_FAITH_FROM_HARVEST</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLAYER_FAITH_FROM_REMOVE_FEATURE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_PLAYER_FREE_RESOURCE_EXTRACTED</td>
	<td rowspan="2">PLAYERS</td>
	<td>ResourceType</td>
	<td>String</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLAYER_RANDOM_CIVIC</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLAYER_RANDOM_TECHNOLOGY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLAYER_RELIGIOUS_PRESSURE_GREAT_PERSON_ACTIVATED</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLAYER_SPECIFIC_TECH_BOOST_GREAT_PERSON</td>
	<td rowspan="1">PLAYERS</td>
	<td>TechType</td>
	<td>String</td>
	<td>[Technologies.TechnologyType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLAYER_SPECIFIC_TECHNOLOGY</td>
	<td rowspan="1">PLAYERS</td>
	<td>TechType</td>
	<td>String</td>
	<td>[Technologies.TechnologyType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_PLAYER_YIELD_PERCENT_UNIT_COST</td>
	<td rowspan="2">PLAYERS</td>
	<td>UnitCostPercent</td>
	<td>Integer</td>
	<td>[Technologies.TechnologyType]</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Technologies.TechnologyType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PLOT</td>
	<td rowspan="1">PLOTS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_GRANT_POLICY</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_PRODUCTION_IN_CITY</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>KeepOverflow</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_PROMOTION</td>
	<td rowspan="1">UNITS</td>
	<td>PromotionType</td>
	<td>String</td>
	<td>[Promotions.PromotionType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_RANDOM_BASE_PROMOTION</td>
	<td rowspan="1">UNITS</td>
	<td>UnitType</td>
	<td>String</td>
	<td>[Promotions.PromotionType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_RANDOM_CIVIC_BOOST_BY_ERA</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>EndEraType</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="Argument">
	<td>StartEraType</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_RANDOM_CIVIC_BOOST_ON_NEW_ERA</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ApplyImmediately</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_RANDOM_TECHNOLOGY_BOOST_BY_ERA</td>
	<td rowspan="3">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>EndEraType</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="Argument">
	<td>StartEraType</td>
	<td>String</td>
	<td>[Eras.EraType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_RANDOM_TECHNOLOGY_BOOST_ON_NEW_ERA</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ApplyImmediately</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_RELIC</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_RELIGIOUS_PRESSURE_BURST</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Range</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_ROUTE_IN_RADIUS</td>
	<td rowspan="2"></td>
	<td>Radius</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>RouteType</td>
	<td>String</td>
	<td>[Routes.RouteType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_SPY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_STRENGTH_PER_ADJACENT_UNIT_TYPE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">EFFECT_GRANT_TECHNOLOGY</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_UNIT_BY_CLASS</td>
	<td rowspan="1">CITIES</td>
	<td>UnitPromotionClassType</td>
	<td>String</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_UNIT_BY_DOMAIN</td>
	<td rowspan="1">CITIES</td>
	<td>UnitDomain</td>
	<td>String</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_UNIT_IN_CITY</td>
	<td rowspan="3">CITIES</td>
	<td>AllowUniqueOverride</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_UNIT_OF_CLASS_AND_APPLY_ABILITY</td>
	<td rowspan="2">CITIES</td>
	<td>ModifierId</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>UnitPromotionClassType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_GRANT_UNIT_TYPE_UNLIMITED_PROMOTION_CHOICES</td>
	<td rowspan="1">PLAYERS</td>
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_UNIT_WITH_EXPERIENCE</td>
	<td rowspan="3">PLAYERS</td>
	<td>Experience</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>UniqueOverride</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>String</td>
	<td>[Units.UnitType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_UNIT_YIELD_ADJACENT_FEATURES</td>
	<td rowspan="3">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>FeatureType</td>
	<td>String</td>
	<td>[Features.FeatureType]</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_GRANT_UNIT_YIELD_ADJACENT_NATURAL_WONDERS</td>
	<td rowspan="2">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_UNIT_YIELD_ADJACENT_TERRAINS</td>
	<td rowspan="3">UNITS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td>[Terrains.TerrainType]</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_YIELD</td>
	<td rowspan="3">ANY</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>Scale</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_YIELD_BASED_ON_CURRENT_YIELD_RATE</td>
	<td rowspan="3">ANY</td>
	<td>Multiplier</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>YieldToBaseOn</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="Argument">
	<td>YieldToGrant</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_GRANT_YIELD_PER_GREAT_WORK_IN_CITY</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>GreatWorkObjectType</td>
	<td>String</td>
	<td>[GreatWorkObjectTypes.GreatWorkObjectType]</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_IMPROVEMENT_ADJACENCY</td>
	<td rowspan="6">DISTRICTS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>Description</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>ImprovementType</td>
	<td>String</td>
	<td>[Improvements.ImprovementType]</td>
</tr>
<tr class="Argument">
	<td>TilesRequired</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">EFFECT_KILL_EMERGENCY_TARGET_SPIES_IN_CITY</td>
	<td rowspan="1">CITIES</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_MAP_REMOVE_CLIFFS_IN_DIRECTION</td>
	<td rowspan="1"></td>
	<td>Radius</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_MOUNTAIN_PORTAL</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_PLAYER_SEND_GOLD_TO_EMERGENCIES_OF_TYPE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>EmergencyType</td>
	<td>String</td>
	<td>[Emergencies.EmergencyType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_REPLACE_PLAYER_GOVERNMENT_SLOT_TYPE</td>
	<td rowspan="3">PLAYERS</td>
	<td>AddedGovernmentSlotType</td>
	<td>String</td>
	<td>[GovernmentSlots.GovernmentSlotType]</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>ReplacedGovernmentSlotType</td>
	<td>String</td>
	<td>[GovernmentSlots.GovernmentSlotType]</td>
</tr>
<tr class="Argument">
	<td>ReplacesAll</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_RESTORE_UNIT_MOVEMENT</td>
	<td rowspan="1">UNITS</td>
	<td>MovementOnly</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">EFFECT_RIVER_ADJACENCY</td>
	<td rowspan="5">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="5"></td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>Description</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>TilesRequired</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_SETTLED_FOREIGN_CONTINENT_UNIT_CLASS</td>
	<td rowspan="1"></td>
	<td>UnitPromotionClassType</td>
	<td>String</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="6"></td>
	<td rowspan="6">EFFECT_TERRAIN_ADJACENCY</td>
	<td rowspan="6">CITIES</td>
	<td>Amount</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="6"></td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6">✓</td>
	<td rowspan="6"></td>
</tr>
<tr class="Argument">
	<td>Description</td>
	<td>String</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>String</td>
	<td>[Districts.DistrictType]</td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>String</td>
	<td>[Terrains.TerrainType]</td>
</tr>
<tr class="Argument">
	<td>TilesRequired</td>
	<td>Integer</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>String</td>
	<td>[Yields.YieldType]</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_TRADE_ROUTE_CANCEL</td>
	<td rowspan="1"></td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">EFFECT_TRADE_ROUTE_DISABLE</td>
	<td rowspan="3"></td>
	<td>Domestic</td>
	<td>Boolean</td>
	<td></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>InternationalMajors</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="Argument">
	<td>InternationalMinors</td>
	<td>Boolean</td>
	<td></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_TREAT_CAPITAL_AS_HOLY_CITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Value</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_TREAT_HOLY_SITE_AS_HOLY_CITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>Value</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">EFFECT_TRIGGER_GAME_MECHANIC</td>
	<td rowspan="1">ANY</td>
	<td>MechanicName</td>
	<td>String</td>
	<td>GenerateLandAntiquities<br>GenerateSeaAntiquities</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">EFFECT_UNIT_TELEPORT</td>
	<td rowspan="2">UNITS</td>
	<td>MinRange</td>
	<td>Integer</td>
	<td></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MaxRange</td>
	<td>Integer</td>
	<td></td>
</tr>
</tbody></table></div>