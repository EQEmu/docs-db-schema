| Column        | Data Type | Description                                                                         |
| ------------- | --------- | ----------------------------------------------------------------------------------- |
| id            | int       | Unique Instance Identifier                                                          |
| zone          | int       | [Zone Identifier](https://eqemu.gitbook.io/server/categories/reference-lists/zones) |
| version       | tinyint   | Version                                                                             |
| is_global     | tinyint   | Is Global: 0 = False, 1 = True                                                      |
| start_time    | int       | Start Time UNIX Timestamp                                                           |
| duration      | int       | Duration in Seconds                                                                 |
| never_expires | tinyint   | Never Expires: 0 = False, 1 = True                                                  |