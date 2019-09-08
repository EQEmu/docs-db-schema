| Column         | Data Type | Description                                      |
| -------------- | --------- | ------------------------------------------------ |
| character_id   | int       | [Unique Character Identifier](character_data.md) |
| slot_id        | tinyint   | Buff Slot                                        |
| spell_id       | smallint  | [Buff Spell ID](spells_new.md)                   |
| caster_level   | tinyint   | Caster Level                                     |
| caster_name    | varchar   | Caster Name                                      |
| ticsremaining  | int       | Tics Remaining                                   |
| counters       | int       | Counters                                         |
| numhits        | int       | Number of Hits                                   |
| melee_rune     | int       | Melee Rune                                       |
| magic_rune     | int       | Magic Rune                                       |
| persistent     | tinyint   | Persistent: 0 = False, 1 = True                  |
| dot_rune       | int       | Damage Over Time Rune                            |
| caston_x       | int       | X Coordinate                                     |
| caston_y       | int       | Y Coordinate                                     |
| caston_z       | int       | Z Coordinate                                     |
| ExtraDIChance  | int       |                                                  |
| instrument_mod | int       | Instrument Modifier                              |