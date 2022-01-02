---
title: List of Requirement Types
description: 
published: true
date: 2022-01-02T15:30:59.987Z
tags: database modding, requirements, civilization vi
editor: markdown
dateCreated: 2022-01-02T15:30:59.987Z
---

# List of Requirement Types
This table has been adapted from [ChimpanG's Modding Companion](https://docs.google.com/spreadsheets/d/1hQ8zlEHl1nfjCWvKqOlkDACezu5-igfQkVcOxeE_KG0/edit#gid=1678767919).

---

<div class="html-custom-table">
<table>
<thead>
	<tr>
		<th>Status</th>
		<th>RequirementType</th>
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
	<td rowspan="1">REQUIREMENT_ALLIANCE_CITY_HAS_TRADE_ROUTE_WITH_ALLY</td>
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
	<td rowspan="1">REQUIREMENT_ALLY</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_ALWAYS_MET</td>
	<td rowspan="1">ANY</td>
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
	<td rowspan="1">REQUIREMENT_ATTACKER_PLOT_HAS_ANY_DISTRICT</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_ATTACKER_PLOT_IMPROVEMENT_DEFENSE_STRENGTH</td>
	<td rowspan="1">PLOTS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_ATTACKER_PLOT_IMPROVEMENT_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>ImprovementType</td>
	<td>[Improvements.ImprovementType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_BUILDING_TAG_MATCHES</td>
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
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_BUILDING_TYPE_MATCHES</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_CONVERTED</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_FOLLOWS_PANTHEON</td>
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
	<td rowspan="1">REQUIREMENT_CITY_FOLLOWS_RELIGION</td>
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
	<td rowspan="1">REQUIREMENT_CITY_HAS_ANY_WONDER</td>
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
	<td rowspan="3">REQUIREMENT_CITY_HAS_BUILDING</td>
	<td rowspan="3">CITIES</td>
	<td>BuildingType</td>
	<td>[Buildings.BuildingType]</td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>ExactMatch</td>
	<td>[Buildings.BuildingType]</td>
	<td>Boolean</td>
</tr>
<tr class="Argument">
	<td>MustBeFunctioning</td>
	<td>[Buildings.BuildingType]</td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_CITY_HAS_DISTRICT</td>
	<td rowspan="3">CITIES</td>
	<td>DistrictType</td>
	<td>[Districts.DistrictType]</td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>ExactMatch</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="Argument">
	<td>MustBeFunctioning</td>
	<td>[Buildings.BuildingType]</td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_HAS_FEATURE</td>
	<td rowspan="1">CITIES</td>
	<td>FeatureType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_HAS_FULL_LOYALTY</td>
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
	<td rowspan="1">REQUIREMENT_CITY_HAS_GARRISON_UNIT</td>
	<td rowspan="1">CITIES</td>
	<td>MilitaryFormation</td>
	<td>ARMY_MILITARY_FORMATION
CORPS_MILITARY_FORMATION</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_HAS_GOVERNMENT_BUILDING_TIER</td>
	<td rowspan="1">CITIES</td>
	<td>GovernmentBuildingTier</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_HAS_GOVERNOR</td>
	<td rowspan="1">CITIES</td>
	<td>Established</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_CITY_HAS_GOVERNOR_WITH_X_TITLES</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Established</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_CITY_HAS_HIGH_ADJACENCY_DISTRICT</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>DistrictType</td>
	<td>[Districts.DistrictType]</td>
	<td>String</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>[Yields.YieldType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_HAS_NATIONAL_PARK</td>
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
	<td rowspan="1">REQUIREMENT_CITY_HAS_RESOURCE_TYPE_IMPROVED</td>
	<td rowspan="1">CITIES</td>
	<td>ResourceType</td>
	<td>[Resources.ResourceType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_CITY_HAS_SPECIFIC_GOVERNOR_PROMOTION_TYPE</td>
	<td rowspan="2">CITIES</td>
	<td>GovernorPromotionType</td>
	<td>[GovernorPromotions.GovernorPromotionType]</td>
	<td>String</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Established</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_CITY_HAS_X_FEATURE_TYPE</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>FeatureType</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_HAS_X_POPULATION</td>
	<td rowspan="1">CITIES</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_CITY_HAS_X_SPECIALTY_DISTRICTS</td>
	<td rowspan="2">CITIES</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MustBeFunctioning</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_CITY_HAS_X_TERRAIN_TYPE</td>
	<td rowspan="3">CITIES</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Hills</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="Argument">
	<td>TerrainType</td>
	<td>[Terrains.TerrainType]</td>
	<td>String</td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_CITY_IS_CAPITAL</td>
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
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_CITY_IS_ORIGINAL_CAPITAL</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_IS_ORIGINAL_OWNER</td>
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
	<td rowspan="1">REQUIREMENT_CITY_IS_OWNER_CAPITAL_CONTINENT</td>
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
	<td rowspan="1">REQUIREMENT_CITY_IS_POWERED</td>
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
	<td rowspan="1">REQUIREMENT_CITY_LIBERATED</td>
	<td rowspan="1">CITIES</td>
	<td>OnlyOwnersCity</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_CITY_LOCATION_MATCHES</td>
	<td rowspan="2">CITIES</td>
	<td>X</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Y</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_OCCUPIED</td>
	<td rowspan="1">CITIES</td>
	<td>OnlyOwnersCity</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_OCCUPIED_FRIEND</td>
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
	<td rowspan="1">REQUIREMENT_CITY_OWNER_ALLY_AT_WAR</td>
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
	<td rowspan="1">REQUIREMENT_CITY_RAZED</td>
	<td rowspan="1">CITIES</td>
	<td>OnlyOwnersCity</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CITY_TRANSFER_TYPE_MATCHES</td>
	<td rowspan="1">CITIES</td>
	<td>TransferType</td>
	<td>BY_COMBAT
BY_COMBAT_ORIGINAL_OWNER
BY_COMBAT_OWNER_BEFORE_OCCUPATION
BY_CULTURAL_IDENTITY
BY_GIFT
BY_LIBERATION
BY_SETTLER</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_CIV_TAG_MATCHES</td>
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
	<td rowspan="1">REQUIREMENT_CIV_TYPE_MATCHES</td>
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
	<td rowspan="2">REQUIREMENT_CIVILIZATION_LEVEL</td>
	<td rowspan="2">PLAYERS</td>
	<td>OpponentCivLevel</td>
	<td></td>
	<td>String</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>OwnerCivLevel</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_COLLECTION_ALL_MET</td>
	<td rowspan="3">ANY</td>
	<td>CollectionType</td>
	<td></td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinimumCount</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>RequirementSetId</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_COLLECTION_ANY_MET</td>
	<td rowspan="2">ANY</td>
	<td>CollectionType</td>
	<td></td>
	<td>String</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>RequirementSetId</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_COLLECTION_COUNT_ATLEAST</td>
	<td rowspan="3">ANY</td>
	<td>CollectionType</td>
	<td></td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Count</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>RequirementSetId</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_COLLECTION_COUNT_EQUALS</td>
	<td rowspan="3">ANY</td>
	<td>CollectionType</td>
	<td></td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>Count</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>RequirementSetId</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_COLLECTION_COUNT_GREATERTHAN</td>
	<td rowspan="2">ANY</td>
	<td>CollectionType</td>
	<td></td>
	<td>String</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>RequirementSetId</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_COMBAT_ATTACKER_IS_EMERGENCY_MEMBER</td>
	<td rowspan="1">COMBATS</td>
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
	<td rowspan="1">REQUIREMENT_COMBAT_ATTACKER_IS_EMERGENCY_MEMBER_WITH_SCORE</td>
	<td rowspan="1">COMBATS</td>
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
	<td rowspan="1">REQUIREMENT_COMBAT_ATTACKER_IS_PLAYER</td>
	<td rowspan="1">COMBATS</td>
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
	<td rowspan="1">REQUIREMENT_COMBAT_DEFENDER_IS_EMERGENCY_MEMBER</td>
	<td rowspan="1">COMBATS</td>
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
	<td rowspan="1">REQUIREMENT_COMBAT_DEFENDER_IS_EMERGENCY_MEMBER_WITH_SCORE</td>
	<td rowspan="1">COMBATS</td>
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
	<td rowspan="1">REQUIREMENT_COMBAT_DEFENDER_IS_PLAYER</td>
	<td rowspan="1">COMBATS</td>
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
	<td rowspan="1">REQUIREMENT_COMBAT_ENEMY_NOT_ALLIANCE_RELIGION</td>
	<td rowspan="1">COMBATS</td>
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
	<td rowspan="1">REQUIREMENT_COMBAT_TYPE_MATCHES</td>
	<td rowspan="1">COMBATS</td>
	<td>CombatType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_COMBAT_VERSUS_TYPE_MATCHES</td>
	<td rowspan="1">COMBATS</td>
	<td>CombatVersusType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_CULTURE_BOMBED</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_DECLARED_FRIEND</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_DEFENSIVE_PACT</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_DELEGATION</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_DEMAND_RECEIVED</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_DENOUNCED</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_DENOUNCED_FRIEND</td>
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
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_DISTRICT_HAS_BUILDING</td>
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
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_DISTRICT_TAG_MATCHES</td>
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
	<td rowspan="1">REQUIREMENT_DISTRICT_TYPE_MATCHES</td>
	<td rowspan="1">DISTRICTS</td>
	<td>DistrictType</td>
	<td>[Districts.DistrictType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_ESPIONAGE_DETECTED</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_FOUNDED_NO_RELIGION</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_CLIMATE_CHANGE_LEVEL_AT_LEAST</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_ERA_ATLEAST</td>
	<td rowspan="1">PLAYERS</td>
	<td>MinGameEra</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_ERA_ATLEAST_EXPANSION</td>
	<td rowspan="1">PLAYERS</td>
	<td>EraType</td>
	<td>[Eras.EraType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_GAME_ERA_ATMOST</td>
	<td rowspan="1">PLAYERS</td>
	<td>EraType</td>
	<td>[Eras.EraType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_ERA_ATMOST_EXPANSION</td>
	<td rowspan="1">PLAYERS</td>
	<td>EraType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_ERA_IS</td>
	<td rowspan="1">PLAYERS</td>
	<td>EraType</td>
	<td>[Eras.EraType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_HAS_CIVILIZATION_OR_LEADER_TRAIT</td>
	<td rowspan="1">PLAYERS</td>
	<td>TraitType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_GAME_IS_MULTIPLAYER</td>
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
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_GAME_TURN_ATLEAST</td>
	<td rowspan="2">PLAYERS</td>
	<td>AdjustForGameSpeed</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinGameTurn</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_TURN_MAX_REACHED</td>
	<td rowspan="1">PLAYERS</td>
	<td>MaxGameTurn</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_GAME_VICTORY_ENABLED</td>
	<td rowspan="1">PLAYERS</td>
	<td>VictoryType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_GREAT_PERSON_TYPE_MATCHES</td>
	<td rowspan="2">UNITS</td>
	<td>GreatPersonClassType</td>
	<td>[GreatPersonClasses.GreatPersonClassType]</td>
	<td>String</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>TurnsToIgnoreLiberatorTroops</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_HAD_FRIENDLY_MEETING</td>
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
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_LEADER_TAG_MATCHES</td>
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
	<td rowspan="1">REQUIREMENT_LEADER_TYPE_MATCHES</td>
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
	<td rowspan="1">REQUIREMENT_MAP_HAS_FEATURE</td>
	<td rowspan="1">ANY</td>
	<td>FeatureType</td>
	<td>[Features.FeatureType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_MET</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_NEAR_CULTURE_BORDER</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_NEAR_RELIGIOUS_CITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>FriendlyCity</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_NEVER_MET</td>
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
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_NOT_MET</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPEN_BORDERS</td>
	<td rowspan="1">PLAYERS</td>
	<td>GracePeriod</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPPONENT_ERA_AGE_MATCHES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Type</td>
	<td>DARK
GOLDEN
NONE</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPPONENT_ERA_AT_LEAST</td>
	<td rowspan="1">UNITS</td>
	<td>MinimumEraType</td>
	<td>[Eras.EraType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPPONENT_IS_BARBARIAN</td>
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
	<td rowspan="1">REQUIREMENT_OPPONENT_IS_DISTRICT</td>
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
	<td rowspan="1">REQUIREMENT_OPPONENT_IS_FORTIFIED</td>
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
	<td rowspan="1">REQUIREMENT_OPPONENT_IS_MINOR_CIV</td>
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
	<td rowspan="1">REQUIREMENT_OPPONENT_IS_OTHER_RELIGION</td>
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
	<td rowspan="1">REQUIREMENT_OPPONENT_IS_WOUNDED</td>
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
	<td rowspan="1">REQUIREMENT_OPPONENT_UNIT_DOMAIN_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>UnitDomain</td>
	<td>DOMAIN_LAND
DOMAIN_SEA</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPPONENT_UNIT_PROMOTION_CLASS_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>UnitPromotionClass</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPPONENT_UNIT_TAG_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPPONENT_UNIT_TYPE_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>UnitType</td>
	<td>[Units.UnitType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_OPPONENT_WAS_KILLED</td>
	<td rowspan="1">COMBATS</td>
	<td>PlayerIsVictorious</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_ALWAYS_ALLOWED_COMMEMORATION_QUEST</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_AT_WAR_AND_HAS_MET</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_AT_WAR_WITH_EMERGENCY_MEMBER</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_AT_WAR_WITH_NEIGHBOR</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_ATTACKED_CONTINENT</td>
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
	<td rowspan="2">REQUIREMENT_PLAYER_AVERAGE_WALL_LEVEL_THRESHOLD</td>
	<td rowspan="2">PLAYERS</td>
	<td>AboveThreshold</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>AverageWallLevelThreshold</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_BUILT_NEW_WONDER</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_BUILT_WONDER</td>
	<td rowspan="1">PLAYERS</td>
	<td>WonderRatio</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_CAN_EVER_EARN_GREAT_PERSON_CLASS</td>
	<td rowspan="1">PLAYERS</td>
	<td>GreatPersonClass</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">REQUIREMENT_PLAYER_CITY_STATE_PROTECTOR</td>
	<td rowspan="4">PLAYERS</td>
	<td>LowerBound</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>NoLowerBound</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="Argument">
	<td>NoUpperBound</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="Argument">
	<td>UpperBound</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="5"></td>
	<td rowspan="5">REQUIREMENT_PLAYER_CIVILIZED</td>
	<td rowspan="5">PLAYERS</td>
	<td>BelowThreshold</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="5"></td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5">✓</td>
	<td rowspan="5"></td>
</tr>
<tr class="Argument">
	<td>CampToCityDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>ClearedCampValue</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>IgnoredCampValue</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>TotalScoreThreshold</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLAYER_COASTAL_CITIES</td>
	<td rowspan="3">PLAYERS</td>
	<td>BelowPercentage</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinimumCities</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>Percentage</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_COMPETING_MINORS</td>
	<td rowspan="1">PLAYERS</td>
	<td>PercentCompeting</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_CONQUERED_X_CITY_STATES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_CONQUERING_ALLYING_MINORS</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_DEAL_ENACTED</td>
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
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLAYER_DECLARED_WAR</td>
	<td rowspan="3">PLAYERS</td>
	<td>ExcludeEmergencies</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>WarType</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="Argument">
	<td>WhileMet</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLAYER_DEFAULT_DEFEAT</td>
	<td rowspan="3">PLAYERS</td>
	<td>IgnoreCities</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
</tr>
<tr class="Argument">
	<td>IgnoreUnits</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>[Units.UnitType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_DIPLO_VP_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Ratio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLAYER_DISTRICT_THRESHOLD</td>
	<td rowspan="3">PLAYERS</td>
	<td>AboveThreshold</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>DistrictPercentThreshold</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MinDistrictsNeeded</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_DOMINATION_VICTORY</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_ENVIRONMENT</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_ERA_AT_LEAST</td>
	<td rowspan="1">PLAYERS</td>
	<td>EraType</td>
	<td>[Eras.EraType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_EXPLOITATION</td>
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
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_EXPLORATION_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>ExplorationRatio</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_FAVOR_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Ratio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_FINISHED_RESEARCH</td>
	<td rowspan="1">PLAYERS</td>
	<td>TechCivicDifferential</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_FOUNDED_NO_RELIGION</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_FOUNDED_OUR_RELIGION</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_FOUNDED_RELIGION_WITH_BELIEF</td>
	<td rowspan="1">PLAYERS</td>
	<td>BeliefType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_GOT_FIRST_PLACE_IN_EMERGENCY</td>
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
	<td rowspan="2">REQUIREMENT_PLAYER_GOT_GREAT_PERSON</td>
	<td rowspan="2">PLAYERS</td>
	<td>GreatPersonRatio</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HANDICAP_AT_OR_ABOVE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Handicap</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_HAPPINESS_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>HappinessRatio</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_GOT_HIGH_TIER_SCORE_IN_EMERGENCY</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_GOT_LOW_TIER_SCORE_IN_EMERGENCY</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_ACTIVE_ALLIANCE_OF_AT_LEAST_LEVEL</td>
	<td rowspan="1">PLAYERS</td>
	<td>Level</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_AT_LEAST_DIPLO_VIS_LEVEL</td>
	<td rowspan="1">PLAYERS</td>
	<td>Level</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_HAS_AT_LEAST_NUM_BUILDINGS</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>BuildingType</td>
	<td>[Buildings.BuildingType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_AT_LEAST_NUMBER_CITIES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_AT_LEAST_NUM_MILITARY_UNITS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_BUILDING</td>
	<td rowspan="1">PLAYERS</td>
	<td>BuildingType</td>
	<td>[Buildings.BuildingType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_CITY_ON_EMERGENCY_PLOT_CONTINENT</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_CIVIC</td>
	<td rowspan="1">PLAYERS</td>
	<td>CivicType</td>
	<td>[Civics.CivicType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_CIVILIZATION_OR_LEADER_TRAIT</td>
	<td rowspan="1">PLAYERS</td>
	<td>TraitType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_COMP_STOMP_VICTORY</td>
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
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_HAS_COMPLETED_PROJECT</td>
	<td rowspan="2">PLAYERS</td>
	<td>MinimumCompletions</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>ProjectType</td>
	<td>[Projects.ProjectType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_DARK_AGE</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_DESIRED_LUXURY</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_DISTRICT</td>
	<td rowspan="1">PLAYERS</td>
	<td>DistrictType</td>
	<td>[Districts.DistrictType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_ENVOY_WITH_EMERGENCY_DATA_PLAYER</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_FEATURE</td>
	<td rowspan="1">PLAYERS</td>
	<td>FeatureType</td>
	<td>[Features.FeatureType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_GIVEN_INFLUENCE_TOKENS</td>
	<td rowspan="1">PLAYERS</td>
	<td>MinimumTokens</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_GIVEN_MOST_INFLUENCE_TOKENS</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_GOLDEN_AGE</td>
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
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_GOLDEN_HORDE_VICTORY</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_GREAT_PERSON</td>
	<td rowspan="1">PLAYERS</td>
	<td>GreatPersonIndividual</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_HIGHEST_SCORE</td>
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
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_HAS_MANY_ALLIANCES</td>
	<td rowspan="2">PLAYERS</td>
	<td>ChecKForFewer</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinOwnerAlliances</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_MET</td>
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
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_MOST_PROMOTION_CLASS</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_MOST_RELIGION_FOLLOWERS</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_MOST_TERRITORY</td>
	<td rowspan="1">PLAYERS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_MOST_WMD_CITY_HITS</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_PANTHEON</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_RESOURCE_IMPROVED</td>
	<td rowspan="1">PLAYERS</td>
	<td>ResourceType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_RESOURCE_OWNED</td>
	<td rowspan="1">PLAYERS</td>
	<td>ResourceType</td>
	<td>[Resources.ResourceType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_RESOURCE_VISIBILITY</td>
	<td rowspan="1">PLAYERS</td>
	<td>ResourceType</td>
	<td>[Resources.ResourceType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_SAME_GOVERNMENT</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_SCIENCE_VICTORY_POINTS</td>
	<td rowspan="1">PLAYERS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_HAS_TECHNOLOGY</td>
	<td rowspan="1">PLAYERS</td>
	<td>TechnologyType</td>
	<td>[Technologies.TechnologyType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IN_JOINT_EMERGENCY</td>
	<td rowspan="1">PLAYERS</td>
	<td>HostileOnly</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_INCOME_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>YieldRatio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_AT_LEAST_ALLIANCE_LEVEL_WITH_EMERGENCY_PLAYER</td>
	<td rowspan="1">PLAYERS</td>
	<td>Level</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_AT_PEACE</td>
	<td rowspan="1">PLAYERS</td>
	<td>Min Turns</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_AT_PEACE_WITH_ALL_MAJORS</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_AT_WAR</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_IS_ATTACKING</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_BARBARIAN</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_CLOSE_TO_VICTORY</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_EMERGENCY_MEMBER_WITH_SCORE</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_IS_EMERGENCY_TARGET</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_IS_HUMAN</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_MAJOR</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_MINOR</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_NEIGHBOR</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_IS_NOT_WARMONGER</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_RELIGION_FOUNDER</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_SAME_RELIGION</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_SAME_SEX</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_IS_SHARING_INFO</td>
	<td rowspan="1">PLAYERS</td>
	<td>SharingInfoWell</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_SUZERAIN</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_SUZERAIN_BONUS_ENABLED</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_IS_SUZERAIN_OF_X</td>
	<td rowspan="1">PLAYERS</td>
	<td>LeaderType</td>
	<td>[Leaders.LeaderType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_IS_SUZERAIN_X_TYPE</td>
	<td rowspan="2">PLAYERS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>LeaderType</td>
	<td>[Leaders.LeaderType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_TEAM_MEMBER</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_IS_WINNING_ANY_VICTORY</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_LEADER_TAG_MATCHES</td>
	<td rowspan="1">PLAYERS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_LEADER_TYPE_MATCHES</td>
	<td rowspan="1">PLAYERS</td>
	<td>LeaderType</td>
	<td>[Leaders.LeaderType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_MAJORITY_RELIGION_IS_OWNER</td>
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
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLAYER_MEETS_SCORE_THRESHOLD</td>
	<td rowspan="3">PLAYERS</td>
	<td>ExtraIncrementHighestDifficulty</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>IncrementPerDifficulty</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>ScoreLowestDifficulty</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_MET_X_TURNS_AGO</td>
	<td rowspan="1">PLAYERS</td>
	<td>TurnsAgo</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLAYER_MILITARY_STRENGTH_LEAD</td>
	<td rowspan="3">PLAYERS</td>
	<td>DomainType</td>
	<td></td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>StrengthRatio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">REQUIREMENT_PLAYER_MOUNTAIN_CITIES</td>
	<td rowspan="4">PLAYERS</td>
	<td>BelowPercentage</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>DistanceToMountain</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MinimumCities</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>Percentage</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_NOT_COMPETING_MINORS</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_NOT_INVOLVED_MINORS</td>
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
	<td rowspan="4"></td>
	<td rowspan="4">REQUIREMENT_PLAYER_NUKE_LOVER</td>
	<td rowspan="4">PLAYERS</td>
	<td>BelowThreshold</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>BuiltNukeValue</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>TotalScoreThreshold</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>UsedNukeValue</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_ON_NON_HOME_CONTINENT</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_OWNS_OBJECT</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_PEACEFUL_ON_CONTINENT</td>
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
	<td rowspan="2">REQUIREMENT_PLAYER_PILLAGE_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Ratio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_POPULATION_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>PopulationRatio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_RELIGION_NOT_RECEIVED</td>
	<td rowspan="1">PLAYERS</td>
	<td>FoundingDelay</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_RELIGION_RECEIVED</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_SHARES_HOME_CONTINENT</td>
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
<tr class="EffectType EffectType_Removed">
	<td rowspan="1">⛔</td>
	<td rowspan="1">REQUIREMENT_PLAYER_STANDING_ARMY_LEAD</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_TEAM_MEMBER</td>
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
	<td rowspan="1">REQUIREMENT_PLAYER_TURN_STARTED</td>
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
	<td rowspan="2">REQUIREMENT_PLAYER_TYPE_MATCHES</td>
	<td rowspan="2">PLAYERS</td>
	<td>CivilizationType</td>
	<td></td>
	<td>String</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>LeaderType</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLAYER_TOURISM_LEAD</td>
	<td rowspan="2">PLAYERS</td>
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>Ratio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLAYER_WITH_SHIELD_OR_ON_IT</td>
	<td rowspan="1">PLAYERS</td>
	<td>AgreementValue</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLAYER_YIELD_LEAD</td>
	<td rowspan="3">PLAYERS</td>
	<td>MinimumDelta</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>YieldRatio</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>YieldType</td>
	<td>[Yields.YieldType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_ADJACENT_BUILDING_TYPE_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>BuildingType</td>
	<td>[Buildings.BuildingType]</td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">REQUIREMENT_PLOT_ADJACENT_DISTRICT_TYPE_MATCHES</td>
	<td rowspan="4">PLOTS</td>
	<td>DistrictType</td>
	<td>[Districts.DistrictType]</td>
	<td>String</td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MustBeFunctioning</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_ADJACENT_FEATURE_TYPE_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>FeatureType</td>
	<td>[Features.FeatureType]</td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_FRIENDLY_TERRITORY</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_ADJACENT_FRIENDLY_UNIT_TAG_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>Tag</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="4"></td>
	<td rowspan="4">REQUIREMENT_PLOT_ADJACENT_FRIENDLY_UNIT_TYPE_MATCHES</td>
	<td rowspan="4">PLOTS</td>
	<td>IncludeCenter</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="4"></td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4">✓</td>
	<td rowspan="4"></td>
</tr>
<tr class="Argument">
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>[Units.UnitType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_ADJACENT_IMPROVEMENT_TYPE_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>ImprovementType</td>
	<td>[Improvements.ImprovementType]</td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_ADJACENT_RESOURCE_CLASS_TYPE_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>ResourceClassType</td>
	<td>[Resources.ResourceClassType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_ADJACENT_TERRAIN_TYPE_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>TerrainType</td>
	<td></td>
	<td>String</td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_COAST</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_LAKE</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_MOUNTAIN</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_NATURAL_WONDER</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_OWNER</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_OWNER_AT_WAR</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_RIVER</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_ADJACENT_TO_WONDER</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_ADJACENT_UNIT_TYPE_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>MaxRange</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinRange</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>[Units.UnitType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_ANY_ADJACENT_RESOURCE</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_DISTRICT_IS_DEFENDED</td>
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
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_PLOT_DISTRICT_IS_FUNCTIONING</td>
	<td rowspan="1">PLOTS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_DISTRICT_TAG_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_DISTRICT_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>DistrictType</td>
	<td>[Districts.DistrictType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_FEATURE_TAG_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_FEATURE_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>FeatureType</td>
	<td>[Features.FeatureType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_HAS_ANY_DISTRICT</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_HAS_ANY_FEATURE</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_HAS_ANY_IMPROVEMENT</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_HAS_ANY_RESOURCE</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_HAS_FALLOUT</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_IMPROVED_RESOURCE_CLASS_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>ResourceClassType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_IMPROVEMENT_TAG_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_IMPROVEMENT_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>ImprovementType</td>
	<td>[Improvements.ImprovementType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_IS_APPEAL_BETWEEN</td>
	<td rowspan="2">PLOTS</td>
	<td>MaximumAppeal</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>MinimumAppeal</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_IS_COAST</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_IS_COASTAL_LAND</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_IS_FRESH_WATER</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_IS_HILLS</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_IS_IMPASSABLE</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_IS_LAKE</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_IS_MOUNTAIN</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_IS_OWNER_CAPITAL_CONTINENT</td>
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
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_NEAR_CAPITAL</td>
	<td rowspan="2">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="EffectType">
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_PLOT_NEARBY_UNIT_TAG_MATCHES</td>
	<td rowspan="3">PLOTS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>Tag</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="2">❔</td>
	<td rowspan="2">REQUIREMENT_PLOT_PROPERTY_MATCHES</td>
	<td rowspan="2">PLOTS</td>
	<td>PropertyName</td>
	<td></td>
	<td>String</td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument EffectType_Untested">
	<td>PropertyMinimum</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_RESOURCE_CLASS_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>ResourceClassType</td>
	<td>[Resources.ResourceClassType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_RESOURCE_TAG_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_RESOURCE_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>ResourceType</td>
	<td>[Resources.ResourceType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_RESOURCE_VISIBLE</td>
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
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_TERRAIN_CLASS_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>TerrainClass</td>
	<td>[TerrainClasses.TerrainClassType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_TERRAIN_TYPE_MATCHES</td>
	<td rowspan="1">PLOTS</td>
	<td>TerrainType</td>
	<td>[Terrains.TerrainType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_UNIT_CITY_HAS_ANY_DISTRICT</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_UNIT_CITY_HAS_DISTRICT_SAME_OWNER</td>
	<td rowspan="1">PLOTS</td>
	<td>DistrictType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_PLOT_UNIT_EMBARKED</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="1">REQUIREMENT_PLOT_UNIT_FLANKED</td>
	<td rowspan="1">PLOTS</td>
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
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_PLOT_UNIT_TYPE_MATCHES</td>
	<td rowspan="2">PLOTS</td>
	<td>LayerIndex</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2"></td>
</tr>
<tr class="Argument">
	<td>UnitType</td>
	<td>[Units.UnitType]</td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="2"></td>
	<td rowspan="2">REQUIREMENT_REQUIREMENTSET_IS_MET</td>
	<td rowspan="2">ANY</td>
	<td>OnlyOwnersCity</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="2"></td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
	<td rowspan="2">✓</td>
</tr>
<tr class="Argument">
	<td>RequirementSetId</td>
	<td></td>
	<td>String</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_RESIDENT_EMBASSY</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_SPECIFIC_LEADER_ELIMINATED</td>
	<td rowspan="1">ANY</td>
	<td>LeaderType</td>
	<td>[Leaders.LeaderType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_TEAM_CONQUERED_X_CITY_STATES</td>
	<td rowspan="1">TEAMS</td>
	<td>Amount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_TEAM_DIPLOMATIC_VICTORY</td>
	<td rowspan="1">TEAMS</td>
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
	<td rowspan="1">REQUIREMENT_TEAM_DOMINATION_VICTORY</td>
	<td rowspan="1">TEAMS</td>
	<td></td>
	<td></td>
	<td></td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_TEAM_HAS_ANCIENT_RIVALS_VICTORY</td>
	<td rowspan="1">TEAMS</td>
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
	<td rowspan="1">REQUIREMENT_TEAM_HAS_HIGHEST_SCORE</td>
	<td rowspan="1">TEAMS</td>
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
	<td rowspan="1">REQUIREMENT_TEAM_HAS_MOST_PROMOTION_CLASS</td>
	<td rowspan="1">TEAMS</td>
	<td>PromotionClass</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_TEAM_HAS_MOST_RELIGION_FOLLOWERS</td>
	<td rowspan="1">TEAMS</td>
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
	<td rowspan="1">REQUIREMENT_TEAM_HAS_MOST_TERRITORY</td>
	<td rowspan="1">TEAMS</td>
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
	<td rowspan="1">REQUIREMENT_TEAM_HAS_MOST_WMD_CITY_HITS</td>
	<td rowspan="1">TEAMS</td>
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
	<td rowspan="1">REQUIREMENT_TOURISTS_EXCEED_STAYCATIONERS</td>
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
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_TRADE_ROUTE_BETWEEN_ALLIANCE_PARTNERS</td>
	<td rowspan="1">TRADE ROUTES</td>
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
	<td rowspan="1">REQUIREMENT_TRADE_ROUTE_BETWEEN_EMERGENCY_MEMBER_AND_TARGET</td>
	<td rowspan="1">TRADE ROUTES</td>
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
	<td rowspan="1">REQUIREMENT_TRADE_ROUTE_BETWEEN_EMERGENCY_MEMBERS</td>
	<td rowspan="1">TRADE ROUTES</td>
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
	<td rowspan="1">REQUIREMENT_TRADE_ROUTE_DESTINATION_IS_CITY_STATE</td>
	<td rowspan="1">TRADE ROUTES</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_ADJACENT_TO_OWNER_TERRITORY</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_DAMAGE_MINIMUM</td>
	<td rowspan="1">UNITS</td>
	<td>MinimumAmount</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_DOMAIN_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>UnitDomain</td>
	<td>DOMAIN_LAND
DOMAIN_SEA</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_EMBARKED</td>
	<td rowspan="1">UNITS</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_ERA_TYPE_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>EraType</td>
	<td>[Eras.EraType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_FORMATION_CLASS_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>FormationClass</td>
	<td>[UnitFormationClasses.FormationClassType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_HAS_ABILITY</td>
	<td rowspan="1">UNITS</td>
	<td>UnitAbilityType</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType EffectType_Untested">
	<td rowspan="1">❔</td>
	<td rowspan="1">REQUIREMENT_UNIT_HAS_PROMOTION</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_IN_EMERGENCY_TARGET_TERRITORY</td>
	<td rowspan="1">UNITS</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_IN_ENEMY_TERRITORY</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_IN_FORMATION</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_IN_OWNER_TERRITORY</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_IS_BARBARIAN</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_IS_COMBAT</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_IS_LEVIED</td>
	<td rowspan="1">UNITS</td>
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
	<td rowspan="1">REQUIREMENT_UNIT_ON_COAST</td>
	<td rowspan="1">UNITS</td>
	<td>Water</td>
	<td></td>
	<td>Boolean</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_ON_HOME_CONTINENT</td>
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
	<td rowspan="3"></td>
	<td rowspan="3">REQUIREMENT_UNIT_PLOT_HAS_NATIONAL_PARK</td>
	<td rowspan="3">UNITS</td>
	<td>MaxDistance</td>
	<td></td>
	<td>Integer</td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3"></td>
	<td rowspan="3">✓</td>
	<td rowspan="3"></td>
</tr>
<tr class="Argument">
	<td>MinDistance</td>
	<td></td>
	<td>Integer</td>
</tr>
<tr class="Argument">
	<td>SameOwner</td>
	<td></td>
	<td>Boolean</td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_PROMOTION_CLASS_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>UnitPromotionClass</td>
	<td>[UnitPromotionClasses.PromotionClassType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_TAG_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>Tag</td>
	<td></td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
<tr class="EffectType">
	<td rowspan="1"></td>
	<td rowspan="1">REQUIREMENT_UNIT_TYPE_MATCHES</td>
	<td rowspan="1">UNITS</td>
	<td>UnitType</td>
	<td>[Units.UnitType]</td>
	<td>String</td>
	<td rowspan="1"></td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1">✓</td>
	<td rowspan="1"></td>
</tr>
</tbody></table></div>