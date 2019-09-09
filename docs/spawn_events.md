| Column      | Data Type | Description                                                                         |
| ----------- | --------- | ----------------------------------------------------------------------------------- |
| id          | int       | Unique Spawn Event Entry Identifier                                                 |
| zone        | varchar   | [Zone Short Name](https://eqemu.gitbook.io/server/categories/reference-lists/zones) |
| cond_id     | mediumint | [Spawn Condition Identifier](spawn_conditions.md)                                   |
| name        | varchar   | Name                                                                                |
| period      | int       | Period                                                                              |
| next_minute | tinyint   | Next Minute                                                                         |
| next_hour   | tinyint   | Next Hour                                                                           |
| next_day    | tinyint   | Next Day                                                                            |
| next_month  | tinyint   | Next Month                                                                          |
| next_year   | int       | Next Year                                                                           |
| enabled     | tinyint   | Enabled: 0 = False, 1 = True                                                        |
| action      | tinyint   | [Action Type](https://eqemu.gitbook.io/server/categories/types/action-types)        |
| argument    | mediumint | Argument: (Based on Action) 0 = Argument Value                                      |
| strict      | tinyint   | Strict Date Criteria: 0 = False, 1 = True                                           |