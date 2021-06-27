# Action_RPG
Action RPG game developed through a Godot Engine [tutorial series](https://youtube.com/playlist?list=PL9FzW-m48fn2SlrW0KoLT4n5egNdX-W9a) by [HeartBeast](https://github.com/uheartbeast).

## Directories
```
    Effects/                - reusable effects.
    Enemies/                - every enemy in custom directory.
    Hurtbox and Hitbox/     - hurtbox and hitbox assets.
    Audio/                  - music and sounds.
    Player/                 - player assets.
    Shadows/                - shadows.
    UI/                     - UI assets.
    World/                  - world assets.
```

## Game Objects

### AutoLoaded
- `PlayerStats`.

### World
The World (at `res://World.tscn`) should have following the main nodes:

- `Background Sprite`.
- `TileMaps`.
- `Camera`.
- `YSort node (needed for Player, Bushes Ysort, Grass Ysort, Trees Ysort and Bats Ysort to be attached here)`.
- `CanvasLayer (needed for the HealthUI to be displayed)`.

## Credits
[Course](https://youtube.com/playlist?list=PL9FzW-m48fn2SlrW0KoLT4n5egNdX-W9a) created by [HeartBeast](https://github.com/uheartbeast).

## Assets
- https://github.com/uheartbeast/youtube-tutorials/tree/master/Action%20RPG
- https://github.com/uheartbeast/youtube-tutorials/blob/master/Action%20RPG/Action%20RPG%20Resources.zip
