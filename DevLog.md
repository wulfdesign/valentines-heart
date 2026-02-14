📝 DevLog: Valentine Heart Project



Project Context

* Timeframe: Built in ~2 hours.
* Goal: Create a "lightly interactive" surprise for a partner with a shiny, plastic/chocolate-like aesthetic.



Evolution of the Heart

1. Phase 1 (The Winner): Initial version using ExtrudeGeometry with low curveSegments and flatShading. This provided the most stable and aesthetically pleasing "low-poly" look.
2. Phase 2 (Experiments): Attempted custom buffer geometries to create more complex facets ("gem-cut"). While interesting, it drifted away from the simple, charming "low-poly" vibe requested.
3. Phase 3 (Final Polish): Added a state-based click handler to reveal the header and footer text sequentially, creating a "storytelling" moment for the recipient.



Technical Challenges



* Momentum: Implementing a decay function so that when the user stops dragging, the heart settles back into a slow, romantic spin rather than stopping abruptly.
* Orientation: Standard Three.js heart shapes are often defined upside down relative to screen coordinates; corrected this using heart.rotation.x = Math.PI.



Updates

* added MIT Licence
* fixed Heart roatation



Roadmap (future updates)

* custom heart mesh
* candy colored hearts
* Valentine's Heart Game



