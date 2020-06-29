| Column                | Data Type | Description                                                                                   |
| --------------------- | --------- | --------------------------------------------------------------------------------------------- |
| id                    | int       | Unique Spell Effect Entry Identifier                                                          |
| npc_spells_effects_id | int       | [NPC Spells Effects Identifier](npc_spells_effects.md)                                        |
| spell_effect_id       | smallint  | [Spell Effect Identifier](https://eqemu.gitbook.io/server/categories/spells/spell-effect-ids) |
| minlevel              | tinyint   | Minimum Level                                                                                 |
| maxlevel              | tinyint   | Maximum Level                                                                                 |
| se_base               | int       | Spell Effect Base                                                                             |
| se_limit              | int       | Spell Effect Limit                                                                            |
| se_max                | int       | Spell Effect Maximum                                                                          |