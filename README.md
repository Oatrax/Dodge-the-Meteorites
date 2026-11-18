# Dodge the Meteorites

A small 2D arcade game made in Unity (C#). Fly your ship with the mouse, survive as long as you can, and dodge randomly sized, spinning meteorites — your score is how long you last.

## Gameplay
- Hold the **left mouse button** to thrust toward the cursor; the ship rotates to face it
- Meteorites spawn with random size, speed and spin (smaller ones move faster)
- Collisions trigger explosion / bounce effects; restart from the in-game button

## Tech
- Unity 6 (6000.3), 2D physics (`Rigidbody2D`), Input System, UI Toolkit (score label and restart button)
- Scripts: `Assets/Scripts/PlayerController.cs` (movement, score, game over) and `Obstacle.cs` (randomized meteorite behavior)

## Run
Open the project in Unity 6000.3 or newer via Unity Hub and press Play.
