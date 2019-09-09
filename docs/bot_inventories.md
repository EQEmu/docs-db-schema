| Column              | Data Type | Description                                                                                   |
| ------------------- | --------- | --------------------------------------------------------------------------------------------- |
| inventories_index   | int       | Unique Bot Inventory Identifier                                                               |
| bot_id              | int       | [Bot Identifier](bot_data.md)                                                                 |
| slot_id             | mediumint | [Slot Identifier](https://eqemu.gitbook.io/server/categories/reference-lists/inventory-slots) |
| item_id             | int       | [Item Identifier](items.md)                                                                   |
| inst_charges        | smallint  | Charges                                                                                       |
| inst_color          | int       | Color                                                                                         |
| inst_no_drop        | tinyint   | No Drop: 0 = False, 1=  True                                                                  |
| inst_custom_data    | text      | Custom Data                                                                                   |
| ornament_icon       | int       | Ornamentation Icon                                                                            |
| ornament_id_file    | int       | Ornamentation Item Texture                                                                    |
| ornament_hero_model | int       | Ornamentation Hero's Forge Model                                                              |
| augment_1           | mediumint | Augment Slot 1                                                                                |
| augment_2           | mediumint | Augment Slot 2                                                                                |
| augment_3           | mediumint | Augment Slot 3                                                                                |
| augment_4           | mediumint | Augment Slot 4                                                                                |
| augment_5           | mediumint | Augment Slot 5                                                                                |
| augment_6           | mediumint | Augment Slot 6                                                                                |