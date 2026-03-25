# Flappy Bird Clone (Godot)

A simple Flappy Bird-style game developed using the Godot Engine. This project demonstrates core game development concepts including physics-based movement, procedural obstacle spawning, scoring systems, and UI management.

## Features

* Smooth bird movement with gravity and input control
* Procedural pipe generation
* Collision detection and game over logic
* Score tracking system
* Restart functionality
* Fade transition effect on game over
* Organized scene and script structure

## Technologies Used

* Godot Engine (GDScript)
* Git for version control

## Project Structure

```
res://
├── scenes/
│   ├── main.tscn
│   ├── bird.tscn
│   ├── ground.tscn
│   ├── pipe_pair.tscn
│   ├── pipe_spawner.tscn
│   ├── ui.tscn
│   └── fade.tscn
├── scripts/
│   ├── bird.gd
│   ├── game_manager.gd
│   ├── ground.gd
│   ├── pipe_pair.gd
│   ├── pipe_spawner.gd
│   ├── ui.gd
│   └── fade.gd
├── assets/
│   ├── textures/
│   └── fonts/
└── project.godot
```

## Getting Started

### Prerequisites

* Install the latest version of Godot Engine

### Running the Project

1. Clone the repository:

   ```
   git clone https://github.com/your-username/flappy-bird-godot.git
   ```

2. Open Godot Engine

3. Click "Import" and select the `project.godot` file

4. Run the project

## Controls

* Spacebar or mouse click to make the bird jump



