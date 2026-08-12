# Scaffold Engineering Pro — Modular Learning Source

This folder is a modular learning version of the original single-file HTML source supplied by the user.

## Important
- `original/` contains the source as supplied.
- `index.html` keeps the original UI but loads JavaScript/CSS as separate files.
- `js/viewer/` contains the 3D viewer split into understandable responsibilities.
- The viewer rebuild pipeline explicitly clears/disposes the old scaffold before generating the new one.
- The calculation rules are kept based on the supplied source; this package is not a structural engineering certification tool.

## Recommended study order
1. `index.html`
2. `js/core/constants.js`
3. `js/core/state.js`
4. `js/calculator/dimensions.js`
5. `js/calculator/calculator.js`
6. `js/calculator/independent.js`
7. `js/calculator/tower.js`
8. `js/viewer/scene.js`
9. `js/viewer/geometry.js`
10. `js/viewer/viewer.js`
11. `js/viewer/braces.js`
12. `js/viewer/handrails.js`
13. `js/viewer/platforms.js`
14. `js/export/*`
