# spells\_new

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique Spell Identifier |
| name | varchar | Name |
| player\_1 | varchar | Player\_1 |
| teleport\_zone | varchar | The zone you are teleporting to or the [NPC Name](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/npc_types.md) you want to spawn. |
| you\_cast | varchar | The message sent to others when you cast the spell. |
| other\_casts | varchar | The message seen when someone around you casts the spell. |
| cast\_on\_you | varchar | The message received when the spell is cast on you. |
| cast\_on\_other | varchar | The message recieved when the spell is cast on another. |
| spell\_fades | varchar | The message recieved when the spell fades. |
| range | int | Range |
| aoerange | int | Area of Effect Range |
| pushback | int | Push Back |
| pushup | int | Push Up |
| cast\_time | int | Cast Time in Milliseconds |
| recovery\_time | int | Recovery Time in Seconds |
| recast\_time | int | Recast Time in Seconds |
| buffdurationformula | int | [Buff Duration Formula](https://eqemu.gitbook.io/server/categories/spells/buff-duration-formulas) |
| buffduration | int | Buff Duration |
| AEDuration | int | Area of Effect Duration |
| mana | int | Mana Cost |
| effect\_base\_value1 | int | Effect Base Value 1 |
| effect\_base\_value2 | int | Effect Base Value 2 |
| effect\_base\_value3 | int | Effect Base Value 3 |
| effect\_base\_value4 | int | Effect Base Value 4 |
| effect\_base\_value5 | int | Effect Base Value 5 |
| effect\_base\_value6 | int | Effect Base Value 6 |
| effect\_base\_value7 | int | Effect Base Value 7 |
| effect\_base\_value8 | int | Effect Base Value 8 |
| effect\_base\_value9 | int | Effect Base Value 9 |
| effect\_base\_value10 | int | Effect Base Value 10 |
| effect\_base\_value11 | int | Effect Base Value 11 |
| effect\_base\_value12 | int | Effect Base Value 12 |
| effect\_limit\_value1 | int | Effect Limit Value 1 |
| effect\_limit\_value2 | int | Effect Limit Value 2 |
| effect\_limit\_value3 | int | Effect Limit Value 3 |
| effect\_limit\_value4 | int | Effect Limit Value 4 |
| effect\_limit\_value5 | int | Effect Limit Value 5 |
| effect\_limit\_value6 | int | Effect Limit Value 6 |
| effect\_limit\_value7 | int | Effect Limit Value 7 |
| effect\_limit\_value8 | int | Effect Limit Value 8 |
| effect\_limit\_value9 | int | Effect Limit Value 9 |
| effect\_limit\_value10 | int | Effect Limit Value 10 |
| effect\_limit\_value11 | int | Effect Limit Value 11 |
| effect\_limit\_value12 | int | Effect Limit Value 12 |
| max1 | int | Max 1 |
| max2 | int | Max 2 |
| max3 | int | Max 3 |
| max4 | int | Max 4 |
| max5 | int | Max 5 |
| max6 | int | Max 6 |
| max7 | int | Max 7 |
| max8 | int | Max 8 |
| max9 | int | Max 9 |
| max10 | int | Max 10 |
| max11 | int | Max 11 |
| max12 | int | Max 12 |
| icon | int | Icon |
| memicon | int | Memmed Icon |
| components1 | int | [Item Identifier](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/items.md) |
| components2 | int | [Item Identifier](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/items.md) |
| components3 | int | [Item Identifier](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/items.md) |
| components4 | int | [Item Identifier](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/items.md) |
| component\_counts1 | int | Component Count 1 |
| component\_counts2 | int | Component Count 2 |
| component\_counts3 | int | Component Count 3 |
| component\_counts4 | int | Component Count 4 |
| NoexpendReagent1 | int | If it is a number between 1-4 it means component number 1-4 is a focus and not to expend it. If it is a valid item ID it means this item is a focus as well. |
| NoexpendReagent2 | int | If it is a number between 1-4 it means component number 1-4 is a focus and not to expend it. If it is a valid item ID it means this item is a focus as well. |
| NoexpendReagent3 | int | If it is a number between 1-4 it means component number 1-4 is a focus and not to expend it. If it is a valid item ID it means this item is a focus as well. |
| NoexpendReagent4 | int | If it is a number between 1-4 it means component number 1-4 is a focus and not to expend it. If it is a valid item ID it means this item is a focus as well. |
| formula1 | int | [Formula 1](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula2 | int | [Formula 2](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula3 | int | [Formula 3](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula4 | int | [Formula 4](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula5 | int | [Formula 5](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula6 | int | [Formula 6](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula7 | int | [Formula 7](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula8 | int | [Formula 8](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula9 | int | [Formula 9](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula10 | int | [Formula 10](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula11 | int | [Formula 11](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| formula12 | int | [Formula 12](https://eqemu.gitbook.io/server/categories/spells/base-value-formulas) |
| LightType | int | Light Type |
| goodEffect | int | Good Effect: 0 = Detrimental, 1 = Beneficial, 2 = Beneficial Group Only |
| Activated | int | Activated |
| resisttype | int | [Resist Type](https://eqemu.gitbook.io/server/categories/spells/resist-types) |
| effectid1 | int | [Effect Identifier 1](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid2 | int | [Effect Identifier 2](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid3 | int | [Effect Identifier 3](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid4 | int | [Effect Identifier 4](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid5 | int | [Effect Identifier 5](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid6 | int | [Effect Identifier 6](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid7 | int | [Effect Identifier 7](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid8 | int | [Effect Identifier 8](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid9 | int | [Effect Identifier 9](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid10 | int | [Effect Identifier 10](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid11 | int | [Effect Identifier 11](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| effectid12 | int | [Effect Identifier 12](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| targettype | int | [Target Type](https://eqemu.gitbook.io/server/categories/spells/target-types) |
| basediff | int | Base Difficult Fizzle Adjustment |
| skill | int | [Skill Identifier](https://eqemu.gitbook.io/server/categories/player/skills) |
| zonetype | int | [Zone Type](https://eqemu.gitbook.io/server/categories/zones/zone-types) |
| EnvironmentType | int | [Environment Type](https://eqemu.gitbook.io/server/categories/spells/environment-types) |
| TimeOfDay | int | [Time of Day Type](https://eqemu.gitbook.io/server/categories/spells/time-of-day-types) |
| classes1 | int | Required Level for Warrior |
| classes2 | int | Required Level for Cleric |
| classes3 | int | Required Level for Paladin |
| classes4 | int | Required Level for Shadow Knight |
| classes5 | int | Required Level for Ranger |
| classes6 | int | Required Level for Druid |
| classes7 | int | Required Level for Monk |
| classes8 | int | Required Level for Bard |
| classes9 | int | Required Level for Rogue |
| classes10 | int | Required Level for Shaman |
| classes11 | int | Required Level for Necromancer |
| classes12 | int | Required Level for Wizard |
| classes13 | int | Required Level for Magician |
| classes14 | int | Required Level for Enchanter |
| classes15 | int | Required Level for Beastlord |
| classes16 | int | Required Level for Berserker |
| CastingAnim | int | Casting Animation |
| TargetAnim | int | Target Animation |
| TravelType | int | Travel Type \(Unused\) |
| SpellAffectIndex | int | Spell Affect Index |
| disallow\_sit | int | Disallow Sit: 0 = False, 1 = True |
| deities0 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities1 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities2 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities3 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities4 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities5 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities6 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities7 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities8 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities9 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities10 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities11 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities12 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities13 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities14 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities15 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| deities16 | int | [Deity List](https://eqemu.gitbook.io/server/categories/player/deity-list) |
| field142 | int | Unknown |
| field143 | int | Unknown |
| new\_icon | int | New Icon |
| spellanim | int | Spell Animation |
| uninterruptable | int | Uninterruptable: 0 = False, 1 = True |
| ResistDiff | int | Resist Difference |
| dot\_stacking\_exempt | int | Damage Over Time Stacking Exempt: 0 = False, 1 = True |
| deleteable | int | Deleteable: 0 = False, 1 = True |
| RecourseLink | int | [Recourse Spell Identifier](spells_new.md) |
| no\_partial\_resist | int | No Partial Resist: 0 = False, 1 = True |
| field152 | int | Unknown |
| field153 | int | Unknown |
| short\_buff\_box | int | Short Buff Box: 0 = False, 1 = True |
| descnum | int | [Description Number](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/db_str.md) |
| typedescnum | int | [Type Description Number](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/db_str.md) |
| effectdescnum | int | [Effect Description Number](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/db_str.md) |
| effectdescnum2 | int | [Effect Description Number 2](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/db_str.md) |
| npc\_no\_los | int | NPC No Line of Sight: 0 = False, 1 = True |
| field160 | int | Unknown |
| reflectable | int | Reflectable: 0 = False, 1 = True |
| bonushate | int | Bonus Hate |
| field163 | int | Unknown |
| field164 | int | Unknown |
| ldon\_trap | int | [LDoN Trap Identifier](https://github.com/EQEmu/docs-db-schema/tree/e0eb157dbf5563b03c0faf391abc87ec69239f4a/docs/categories/spells/traps.md) |
| EndurCost | int | Endurance Cost |
| EndurTimerIndex | int | Endurance Timer |
| IsDiscipline | int | Is Discipline: 0 = False, 1 = True |
| field169 | int | Unknown |
| field170 | int | Unknown |
| field171 | int | Unknown |
| field172 | int | Unknown |
| HateAdded | int | Hate Added |
| EndurUpkeep | int | Endurance Upkeep |
| numhitstype | int | [Number of Hits Type](https://eqemu.gitbook.io/server/categories/spells/numhit-types) |
| numhits | int | Number of Hits |
| pvpresistbase | int | PVP Resist Base |
| pvpresistcalc | int | PVP Resist Calc |
| pvpresistcap | int | PVP Resist Cap |
| spell\_category | int | [Spell Category](https://eqemu.gitbook.io/server/categories/spells/spell-groups) |
| field181 | int | Unknown |
| field182 | int | Unknown |
| pcnpc\_only\_flag | int | PC/NPC Only Flag: 0 = Not Applicable, 1 = PCs and Mercs, 2 = NPCs |
| cast\_not\_standing | int | Cast Not Standing: 0 = False, 1 = True |
| can\_mgb | int | Can Mass Group Buff: 0 = False, 1 = True |
| nodispell | int | No Dispell: 0 = False, 1 = True |
| npc\_category | int | [NPC Spell Category Identifier](https://eqemu.gitbook.io/server/categories/spells/npc-spell-categories) |
| npc\_usefulness | int | NPC Usefulness |
| MinResist | int | Minimum Resistance |
| MaxResist | int | Maximum Resistance |
| viral\_targets | int | Viral Targets |
| viral\_timer | int | Viral Timer |
| nimbuseffect | int | Nimbus Effect |
| ConeStartAngle | int | Cone Start Angle |
| ConeStopAngle | int | Cone Stop Angle |
| sneaking | int | Sneaking: 0 = False, 1 = True |
| not\_extendable | int | Not Extendable: 0 = False, 1 = True |
| field198 | int | Unknown |
| field199 | int | Unknown |
| suspendable | int | Suspendable: 0 = False, 1 = True |
| viral\_range | int | Viral Range |
| songcap | int | Song Cap |
| field203 | int | Unknown |
| field204 | int | Unknown |
| no\_block | int | No Block: 0 = False, 1 = True |
| field206 | int | Unknown |
| spellgroup | int | [Spell Group](https://eqemu.gitbook.io/server/categories/spells/spell-groups) |
| rank | int | Rank |
| field209 | int | Unknown |
| field210 | int | Unknown |
| CastRestriction | int | [Cast Restrictions](https://eqemu.gitbook.io/server/categories/spells/spell-target-restrictions) |
| allowrest | int | Allow Rest: 0 = False, 1 = True |
| InCombat | int | In Combat: 0 = False, 1 = True |
| OutofCombat | int | Out Of Combat: 0 = False, 1 = True |
| field215 | int | Unknown |
| field216 | int | Unknown |
| field217 | int | Unknown |
| aemaxtargets | int | Area of Effect Max Targets |
| maxtargets | int | Max Targets |
| field220 | int | Unknown |
| field221 | int | Unknown |
| field222 | int | Unknown |
| field223 | int | Unknown |
| persistdeath | int | Persist Death: 0 = False, 1 = True |
| field225 | int | Unknown |
| field226 | int | Unknown |
| min\_dist | float | Minimum Distance |
| min\_dist\_mod | float | Minimum Distance Modifier |
| max\_dist | float | Maximum Distance |
| max\_dist\_mod | float | Maximum Distance Modifier |
| min\_range | int | Minimum Range |
| field232 | int | Unknown |
| field233 | int | Unknown |
| field234 | int | Unknown |
| field235 | int | Unknown |
| field236 | int | Unknown |

