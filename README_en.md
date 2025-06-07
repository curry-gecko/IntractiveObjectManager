# InteractiveObjectManager

This repository provides sample scripts for creating interactive objects in **Unity**. Components included here allow you to handle click and drag operations using [UniRx](https://github.com/neuecc/UniRx).

## Features
- `IClickableObject` interface that defines common click and drag callbacks.
- `DraggableObject` base class for objects that can be dragged.
- `ClickEventManager` for detecting mouse interactions.
- `OnObjectReleasedEventManager` for publishing events when two objects are released together.
- Prefabs for quickly adding the managers to a scene.

## Getting Started
1. Import the scripts and prefabs into your Unity project.
2. Place `ClickEventManager` and `OnObjectReleasedEventManager` prefabs in your scene.
3. Derive from `DraggableObject` or implement `IClickableObject` to add custom behaviour.

## License
This project is released under the terms of the MIT License. See `LICENSE` for more details.
