# Technical Architecture

## Engine
Godot 4.7 + GDScript.

## Structure
```
/game/scenes
/game/scripts
/game/systems
/game/entities
/game/player
/game/enemies
/game/items
/game/inventory
/game/ui
/game/world
/game/resources
```

## Architecture
Scenes represent composition. Scripts contain behavior. Systems manage global logic.

## Autoloads
Planned: GameManager, SaveManager, AudioManager, SceneManager, DataManager.

## Data
Use Godot Resources for editable game data.

## Save
Versioned JSON/resource based local saves.

## UI
Independent UI scenes communicating through signals.

## Input
Central input mapping supporting touch controls.

## Animation
Vector assets with reusable animation controllers.

## Audio
Central mixer and resource based audio loading.

## Performance
Mobile-first optimization, object reuse, efficient nodes and memory control.
