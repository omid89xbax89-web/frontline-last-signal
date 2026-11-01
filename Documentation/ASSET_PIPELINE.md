# 3D Asset Pipeline

**Status:** Production standard  
**Mandatory rule:** Graybox approval comes before final materials and textures.

## Asset stages

### Stage 1 — Brief and references
Record the asset name, purpose, approximate dimensions, target engine, visual references, intended use, and license/source requirements.

### Stage 2 — Graybox model
Create geometry with neutral, untextured materials. Do not spend time on final color or decorative texture work yet.

### Stage 3 — Geometry review
Check:
- Overall silhouette and proportions
- Scale against the project reference character / environment
- Openings, structural logic, and visible surfaces
- Normals and obvious mesh defects
- Polygon density appropriate to the asset's screen size
- Collision approach
- Whether the model matches the approved reference

### Stage 4 — Owner approval
Capture screenshots from useful angles and submit them for approval. Record one of:
- `DRAFT`
- `NEEDS_REVISION`
- `APPROVED`

No final material/texture pass before `APPROVED`.

### Stage 5 — UV and materials
Create UVs and assign physically plausible material properties. Keep material count reasonable.

### Stage 6 — Textures
Use licensed or original texture resources. Record resolution, format, source, license, and any required attribution.

### Stage 7 — Lighting and integration
Import into the selected engine, check scale, pivots, material appearance, collisions, and lighting under the actual project settings.

### Stage 8 — Optimization and validation
Check mesh complexity, texture memory, draw calls/material slots, LOD needs, and performance impact. Record test evidence.

## Required asset record

Each asset must have:
- Asset ID and name
- Purpose and target location
- Source / creator
- License and attribution evidence
- Model format and dimensions
- Geometry review status
- Owner approval status
- Texture/material details
- Engine import status
- Optimization notes
- Test evidence and known issues

## Status definitions

- `NOT_STARTED`: no work recorded
- `IN_PROGRESS`: work underway
- `NEEDS_REVISION`: review found issues
- `APPROVED`: owner approved the required stage
- `INTEGRATED`: imported into the project
- `TESTED`: validated with recorded evidence

Never infer approval or testing from a file existing in the repository.
