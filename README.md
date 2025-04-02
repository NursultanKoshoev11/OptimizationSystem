I developed an optimization system in Unreal Engine designed to enhance game performance by dynamically managing in-game resources and actors. This system ensures that only necessary elements are processed, reducing the load on the CPU and GPU while maintaining a seamless gameplay experience.

Key Features:

Actor Visibility Management – dynamically hides or deactivates actors that are out of view to free up resources.

AI and Logic Optimization – stops AI processing for non-essential NPCs or objects when they are not in range.

Level Streaming – loads and unloads parts of the map based on player position to optimize memory usage.

LOD (Level of Detail) System – automatically adjusts the detail of objects based on their distance from the player.

Physics and Collision Optimization – disables physics and collision calculations for distant or inactive objects.

Performance Monitoring – provides real-time FPS and resource usage data to analyze and adjust optimization settings.

Modular Design – allows for easy expansion with additional optimization rules and conditions.

This system significantly improves game stability, FPS, and overall performance, making it an essential tool for large-scale or open-world projects. It is designed to be adaptable, allowing integration into various game types and engine versions.
