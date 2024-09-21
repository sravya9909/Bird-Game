# Bird-Game


### 1. Setting Up the Project
- Unity Installation: I started by downloading and installing the latest version of Unity Hub and Unity Editor.
- New Project: I created a new 2D project in Unity, naming it "Bird Game."

### 2. Importing Assets
- Sprites and Sounds: I gathered necessary assets such as bird sprites, background images, and sound effects (like flapping sounds and background music). These assets were either created or sourced from free asset libraries.
- Importing Assets: I imported these assets into the Unity project by dragging them into the "Assets" folder.

### 3. Creating the Game Scene
- Scene Setup: I set up the main game scene by adding a background image to the scene and adjusting the camera settings to fit the gameplay area.
- Game Objects: I created game objects for the bird and obstacles (like pipes) by dragging the sprite assets into the scene.

### 4. Adding Physics
- Rigidbody2D Component: I added a Rigidbody2D component to the bird object to enable physics interactions, allowing it to respond to gravity.
- Collider Components: I added BoxCollider2D components to both the bird and obstacles to detect collisions.

### 5. Scripting the Bird's Movement
- Creating Scripts: I created a C# script called BirdController to handle the bird's movement.
- Flap Mechanic: In the script, I implemented functionality for the bird to flap upward when the player presses a key (e.g., spacebar or mouse click). This was achieved by applying an upward force using Rigidbody2D.AddForce().

### 6. Implementing Game Logic
- Obstacle Generation: I wrote logic to spawn obstacles at regular intervals, moving them across the screen.
- Collision Detection: The script checked for collisions between the bird and obstacles, triggering game over conditions if they collided.

### 7. Scoring System
- Score Tracking: I implemented a scoring system that incremented points when the bird successfully passes through obstacles.
- UI Elements: I added UI text elements to display the score on-screen.

### 8. Game Over Condition
- Restart Mechanic: I coded a game over screen that appears when the bird collides with an obstacle, along with a button to restart the game.

### 9. Sound Effects and Music
- Audio Sources: I added audio sources to play sound effects for flapping and collisions, as well as background music during gameplay.

### 10. Testing and Refinement
- Playtesting: After implementing all features, I played through the game multiple times, adjusting physics settings, collision detection, and UI elements for better gameplay experience.

### 11. Final Touches
- Polishing Graphics: I ensured that all graphics were aligned properly and that animations (if any) were smooth.
- Build Settings: Finally, I configured build settings for exporting the game to different platforms (e.g., Windows, WebGL).
