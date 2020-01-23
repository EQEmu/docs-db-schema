# merc\_spell\_list\_entries

| Column | Data Type | Description |
| :--- | :--- | :--- |
| merc\_spell\_list\_entry\_id | int | Unique Mercenary Spell List Entry Identifier |
| merc\_spell\_list\_id | int | [Mercenary Spell List Identifier](merc_spell_lists.md) |
| spell\_id | int | [Spell Identifier](../spells/spells_new.md) |
| spell\_type | int | [Spell Type](https://eqemu.gitbook.io/server/categories/types/spell-types) |
| stance\_id | tinyint | [Stance Type Identifier](https://eqemu.gitbook.io/server/categories/types/stance-types) |
| minlevel | tinyint | Minimum Level |
| maxlevel | tinyint | Maximum Level |
| slot | tinyint | Slot |
| procChance | tinyint | Proc Chance: 0 = Never, 100 = Always |

