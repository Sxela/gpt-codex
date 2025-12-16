# gpt-codex

## Running the sphere big bang demo
1. Download or clone this repository.
2. Open `index.html` in any modern desktop browser (Chrome, Firefox, Edge, Safari):
   - Double-click `index.html`, or
   - Drag the file onto an open browser tab.
   - The page pulls Three.js r182 from a CDN, so an internet connection is required on first load.
3. Use the controls at the top to set particle count, gravity, expansion speed (sphere growth rate), and time scale.
   - Particles start evenly scattered on a near-zero-radius sphere with zero tangential velocity; gravity alone moves them while the sphere radius expands at the chosen explosion speed.
   - Mass mean/standard deviation lets you randomize particle weights before the run.
   - Rendering uses instanced meshes and the physics math runs on typed arrays to keep things smooth with larger particle counts.
4. Watch the live stats panel for average/min/max speed, acceleration, and mass across all particles; the inline charts plot
   the average values over time and can be toggled between linear/log scale.
5. Press **Restart** to relaunch from the tiny starting sphere or **Pause/Resume** to toggle animation.

No build steps or server are required; everything runs locally in the browser.
