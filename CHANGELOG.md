# Changelog

## [1.1.0] - 2026-09-30

### Changed
- Minimum Unity version is now 6000.0 (Unity 6)
- Declared package dependencies: XR Interaction Toolkit 3.6.0,
  Input System 1.20.0, XR Plug-in Management 4.5.4, uGUI 2.0.0
- `Langevin` now uses the Input System (`Keyboard.current`) instead of the
  legacy Input Manager, and `FindObjectsByType` instead of the
  obsolete `FindObjectsOfType`
- Assembly definition now references `Unity.InputSystem`,
  `Unity.XR.Interaction.Toolkit`, `Unity.XR.Management`,
  `Unity.TextMeshPro`, and `UnityEngine.UI`

## [1.0.0] - 2026-01-20

### Added
- Langevin thermostat for molecular dynamics
- Marching Cubes mesh generation (v1 & v2)
- Chunk grid spatial partitioning
- KDTree and SpatialHash data structures
- Particle simulation system
- Spring simulation components
- Mesh and volume utilities
