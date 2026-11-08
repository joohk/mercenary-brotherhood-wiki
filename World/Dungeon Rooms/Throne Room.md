---
id: throne_room
type: room_prefab
category: Dungeon Rooms
aliases:
  - throne_room
tags:
  - room/boss
  - type/room_prefab
source: dungeons/room_prefabs.json
height: 13
roles:
  - boss
width: 11
---

An 11×13 prefab dungeon room, used as a boss room.

## Layout

```
###########
#.........#
#..^^^^^..#
#..^^^^^..#
#..^^^^^..#
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
#.........#
###########
```

Legend: `#` wall, `.` floor, `^` raised floor (dais). Corridors (3 wide) punch doorways through the outer wall along the centre row and column.

## Roles

- **Boss** — the far room of the dungeon; exactly one is chosen (the biggest, most dramatic)

## Related

- **Used in:** [[Dungeons]]

*Generated from `dungeons/room_prefabs.json`. Edits will be overwritten — put your own notes in Notes/.*
