# PedestrianSafetyVR

A VR experience focused on pedestrian safety education, built with Unity.

## Requirements

- Unity 6 (6000.x LTS)
- Meta Quest / OpenXR-compatible headset
- Git LFS installed (`brew install git-lfs && git lfs install`)

## Setup

1. Clone the repo:
   ```bash
   git clone <repo-url>
   cd PedestrianSafetyVR
   ```

2. Open the `PedestrianSafetyVR/` folder in Unity Hub as an existing project. Unity will automatically download all packages via Package Manager.

3. Once the project loads, open the main scene from `Assets/Scenes/`.

## Project Structure

```
PedestrianSafetyVR/
├── Assets/
│   ├── Scenes/         # Project scenes
│   ├── VRTemplateAssets/  # VR template assets
│   └── ...
├── Packages/           # Unity package dependencies (auto-restored)
└── ProjectSettings/    # Unity project configuration
```

## Notes

- Large binary files (FBX, PNG, WAV, etc.) are tracked with Git LFS.
- `Library/`, `Temp/`, and `Logs/` are gitignored — Unity regenerates these on first open.
