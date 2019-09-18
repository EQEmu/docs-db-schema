# task\_activities

| Column | Data Type | Description |
| :--- | :--- | :--- |
| taskid | int | [Task Identifier](tasks.md) |
| activityid | int | Activity Identifier: Starts at 0 |
| step | int | Step: 0 = Always Available, &gt;0 = Must Complete Previous |
| activitytype | tinyint | [Activity Type](https://eqemu.gitbook.io/server/categories/types/task-activity-types) |
| target\_name | varchar | Target Name |
| item\_list | varchar | [Item Identifier List](../items/items.md) |
| skill\_list | varchar | [Skill Identifier List](https://eqemu.gitbook.io/server/categories/reference-lists/skills) |
| spell\_list | varchar | [Spell Identifier List](../spells/spells_new.md) |
| description\_override | varchar | Description Override |
| goalid | int | Goal Identifier or [Goal List Identifier](goallists.md) |
| goalmethod | int | Goal Method: 0 = Single Value, 1 = List |
| goalcount | int | Goal Count |
| delivertonpc | int | Deliver To NPC: 0 = No Delivery NPC, &gt;0 = [NPC Type Identifier](../npcs/npc_types.md) |
| zones | varchar | [Zones List](https://eqemu.gitbook.io/server/categories/reference-lists/zones) |
| optional | tinyint | Optional: 0 = False, 1 = True |

