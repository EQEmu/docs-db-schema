| Column            | Data Type | Description                             |
| ----------------- | --------- | --------------------------------------- |
| id                | int       | Unique Entry Identifier                 |
| adventure_id      | smallint  | Unique Adventure Identifier             |
| instance_id       | int       | [Instance Identifier](instance_list.md) |
| count             | smallint  | Count                                   |
| assassinate_count | smallint  | Assassinate Count                       |
| status            | tinyint   | Status                                  |
| time_created      | int       | Time Created UNIX Timestamp             |
| time_zoned        | int       | Time Zoned UNIX Timestamp               |
| time_completed    | int       | Time Completed UNIX Timestamp           |