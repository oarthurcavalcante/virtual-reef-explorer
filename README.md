# Virtual Reef Explorer

A dual-platform VR application showcasing the Great Barrier Reef, built for **7009ICT: Advances in XR Development** at Griffith University, Trimester 1 2026.

The application targets users aged 18–50 who are considering travel to Queensland and aims to deliver an immersive, accessible introduction to reef ecosystems through guided exploration, gaze-based marine life identification, and an in-experience photo capture system.

This is the **umbrella repository** linking the two engine-specific builds. The actual project code lives in the linked repos below.

## Repositories

| Repository | Engine | Size |
|------------|--------|------|
| [virtual-reef-explorer-unity](https://github.com/oarthurcavalcante/virtual-reef-explorer-unity) | Unity 6 LTS (HDRP) | ~1.4 GB |
| [virtual-reef-explorer-unreal](https://github.com/oarthurcavalcante/virtual-reef-explorer-unreal) | Unreal Engine 5 | ~6.5 GB |

Both repositories use **Git LFS** for binary assets. Clone with `git lfs install` configured first, or run `git lfs pull` after a non-LFS clone.

## Team

| Name | Student Number | Role |
|------|---------------|------|
| Angel Jesrani | s5422506 | XR Developer |
| Sandeep Simha Karri | s5364680 | Project Manager |
| Peidong Guo | s5392225 | System Architect |
| Arthur Cavalcante | s5413339 | Team Leader |
| Chun-Yu Huang | s5252367 | Reviewer |

## Documentation

- [`docs/asset-register-unity.xlsx`](docs/asset-register-unity.xlsx) — Unity build asset register (27 entries)
- [`docs/asset-register-unreal.xlsx`](docs/asset-register-unreal.xlsx) — Unreal build asset register (30 entries)
- Design Document — submitted separately as part of Assignment 1

## Project Overview

The application leads users through a six-scene experience:

1. **Beach Orientation** — onboarding scene with a "Start Adventure" prompt
2. **Underwater Descent** — slow, comfortable transition to the seabed
3. **Coral Reef Exploration** — free-movement environment populated with marine life
4. **Marine Life Identification** — gaze-based 2-second dwell triggers an info panel with name, scientific name, habitat, and conservation status
5. **Reef Snapshot** — in-experience photo capture
6. **Trip Summary** — review of captured photos and creatures discovered

Both engine builds implement the same design with platform-appropriate techniques (Unity HDRP + XR Interaction Toolkit, Unreal Lumen + Blueprint visual scripting).

## License

This project is submitted as coursework for 7009ICT at Griffith University. Source code is the work of the team listed above. Third-party assets are credited in the asset registers and remain the property of their respective owners.
