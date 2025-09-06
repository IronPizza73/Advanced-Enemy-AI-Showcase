# Advanced-Enemy-AI-Showcase

An advanced enemy AI system I created. This was one of my first solo projects using Luau and I plan to use it for a game inevitably. The enemy wanders to points and has an aggression that scales on hardpoints located on every player as well as their movement velocity. It also has a pseudo-sound based detection system for when you are near but behind something.

If I recall this AI has some inconsistencies (especially with the vents not breaking chase properly) that I have yet to fix, however it does function for the most part quite smoothly.

Players can crouch peek and sprint. Crouching and sprinting affect enemy detection.

The AI makes use of an API called SimplePath at the moment for visualization, however it'll be custom made at a later date closer to when the game is leaving Pre-Alpha.
