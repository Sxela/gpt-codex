# gpt-codex

## Running the sphere big bang demo
1. Download or clone this repository.
2. Open `index.html` in any modern desktop browser (Chrome, Firefox, Edge, Safari):
   - Double-click `index.html`, or
   - Drag the file onto an open browser tab.
   - The page pulls Three.js r182 from a CDN, so an internet connection is required on first load.
3. Use the controls at the top to set particle count, gravity, explosion speed, and time scale.
   - Optional distribution controls let you define mean/standard deviation for initial mass, velocity magnitude, launch direction (degrees on the tangent plane), and position jitter (percent of radius) so you can tune how random the starting state is.
4. Watch the live stats panel for average/min/max speed, acceleration, and mass across all particles; the inline charts plot
   the average values over time and can be toggled between linear/log scale.
5. Press **Restart** to relaunch from the surface point or **Pause/Resume** to toggle animation.

No build steps or server are required; everything runs locally in the browser.
