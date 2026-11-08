---
id: great_hall
type: room_prefab
category: Dungeon Rooms
aliases:
  - great_hall
tags:
  - room/boss
  - room/hall
  - type/room_prefab
source: dungeons/room_prefabs.json
height: 13
roles:
  - boss
  - hall
width: 11
---

An 11×13 prefab dungeon room, used as a boss room and a hall room.

## Layout

```
###########
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
###########
```

Legend: `#` wall, `.` floor. Corridors (3 wide) punch doorways through the outer wall along the centre row and column.

## Roles

- **Boss** — the far room of the dungeon; exactly one is chosen (the biggest, most dramatic)
- **Hall** — a large open fighting room

## Related

- **Used in:** [[Dungeons]]

*Generated from `dungeons/room_prefabs.json`. Edits will be overwritten — put your own notes in Notes/.*
