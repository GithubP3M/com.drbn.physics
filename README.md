# DRBN Physics Tools

A Unity package providing physics simulation tools for molecular dynamics, mesh generation, and particle systems.

## Features

- **Langevin Thermostat** - Molecular dynamics simulation with thermal noise
- **Marching Cubes** - Isosurface mesh generation
- **Spatial Data Structures** - KDTree, SpatialHash, ChunkGrid
- **Particle Systems** - 3D particle simulation and rendering
- **Spring Simulation** - Spring-based physics
- **Mesh/Volume Utilities** - Loading and processing tools

## Installation

### Via Package Manager (Git URL)
1. Open Package Manager (Window > Package Manager)
2. Click `+` > "Add package from git URL"
3. Enter: `https://github.com/your-username/com.drbn.physics.git`

### Via manifest.json
```json
{
  "dependencies": {
    "com.drbn.physics": "https://github.com/your-username/com.drbn.physics.git"
  }
}
```

## Requirements

- Unity 6000.0+ (Unity 6)
- XR Interaction Toolkit 3.x
- Input System 1.20+
- XR Plug-in Management 4.5+
- uGUI 2.0 (TextMeshPro / UnityEngine.UI)

All dependencies are declared in `package.json` and resolve automatically.
For VR interaction, enable an XR provider (e.g. OpenXR) in
Project Settings > XR Plug-in Management.

## License

MIT License - See LICENSE.md
