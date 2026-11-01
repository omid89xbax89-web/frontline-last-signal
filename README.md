# FRONTLINE: LAST SIGNAL

A cinematic, stylized 3D multiplayer arena-survival game project targeting Android and PC.

> **Project status:** Pre-production / prototype foundation. No production-ready game build or validated 3D assets are included yet.

## Vision

Build a polished third-person/first-person arena experience with:
- A compact, atmospheric coastal-industrial environment.
- Responsive controls designed for both touchscreens and keyboard/mouse.
- Clear objectives, exploration, collection, and competitive survival-style rounds.
- A scalable visual pipeline that balances quality and performance on Android and PC.

The project may take inspiration from broad genre conventions, but must use original maps, characters, names, UI, audio, and assets. Gameplay should remain fictional and stylized rather than reproducing real-world combat procedures or weapon behavior.

## Current production rule

**Approve the untextured model before adding final materials, textures, or lighting.**

Every asset follows this sequence:
1. Reference and requirements
2. Graybox / untextured geometry
3. Scale, silhouette, topology, and collision review
4. Approval
5. UVs and materials
6. Textures and lighting
7. Optimization and in-engine validation

Do not mark an asset approved or tested without recorded evidence.

## Target platforms

- Android
- Windows PC

The engine has not been selected. Unity URP and Unreal Engine will be evaluated with the same small environment benchmark before a decision is made.

## Repository layout

- `Documentation/` — design, technical decisions, and production records
- `Assets/Environment/` — environment models and source files
- `Assets/Materials/` — material and texture resources
- `Assets/Characters/` — character assets
- `Assets/UI/` — interface assets
- `Assets/Audio/` — audio resources
- `Builds/` — validated prototype builds (not source files)

## Quality policy

- A deployment marked READY is not proof that gameplay works.
- Test Android touch controls and PC controls separately.
- Record device, build, test steps, results, and known issues.
- Never label an untested feature as PASS.
- Prefer free and properly licensed resources. Record attribution and license evidence for every external asset.
- Do not spend paid credits or purchase assets without explicit approval.

## First milestone

Create and validate one small coastal-industrial environment blockout. Keep it deliberately small so visual quality, controls, and performance can be tested before expanding the world.

See the documents in `Documentation/` for the workflow and acceptance gates.
