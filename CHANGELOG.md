# Changelog

## Modular fixed learning version
- Split original single-file source into logical modules.
- Preserved original UI and BOQ calculator functions.
- Corrected malformed OrbitControls CDN URL.
- Added explicit scaffold cleanup/disposal before every rebuild.
- Rebuilt viewer from current dimensions instead of reusing old geometry.
- Centered scaffold on X/Z only so ground elevation remains physical.
- Auto-fit camera recalculates near/far and target from current bounding box.
- Split standards, ledgers, platforms, handrails, planks and braces for learning.
