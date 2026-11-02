# Warehouse Graybox v001 — Geometry Review Submission

**Status:** DRAFT — WAITING FOR PROJECT OWNER REVIEW  
**Asset ID:** WAREHOUSE-001-GRAYBOX  
**Review date:** 2026-11-02  
**Source:** Original procedural blockout generated for this project. It is not the Grab3D downloaded model.

## Deliverables

- GLB: `Assets/Environment/Warehouse/Graybox/FRONTLINE_WAREHOUSE_GRAYBOX_v001.glb`
- Preview: `Assets/Environment/Warehouse/Graybox/FRONTLINE_WAREHOUSE_GRAYBOX_v001_preview.jpg`
- Local original preview: `FRONTLINE_WAREHOUSE_GRAYBOX_v001_preview.png`
- Local front preview: `FRONTLINE_WAREHOUSE_GRAYBOX_v001_front.png`

## Structural validation performed

The GLB was reopened with `trimesh` after export.

- Format: glTF Binary 2.0
- File size: 15,040 bytes
- Geometry objects: 26
- Total triangles: 312
- Every mesh contains faces: yes
- Overall bounds: 44.000 × 44.225 × 9.510 m
- Materials: 0
- Embedded images/textures: 0
- All reported bounds are finite.
- The complete bounding box includes the front loading platform/canopy, so it is deeper than the warehouse shell alone.

## Geometry currently included

- Left, right, and rear wall masses
- Front wall piers and three empty loading-bay openings
- Roof slab and simple roof-edge masses
- Front loading platform
- Simple dock bumpers
- Canopy slab and support posts
- Upper front band

## Known limitations

- This is a first-pass blockout, not a finished architectural model.
- No interior layout, detailed doors, windows, roof equipment, pipes, stairs, or small props.
- No engine import, collision, lighting, mobile performance, or gameplay test has been performed.
- The preview is a geometry-review aid, not evidence of final visual quality.
- The model is intentionally untextured and has no final materials.
- The dimensions and silhouette still require owner review.

## External candidate status

Grab3D's separate Warehouse listing advertises a 44.00 × 39.30 × 9.54 m GLB with 32,456 triangles and 2K PBR maps. In this review cycle, its package `LICENSE.txt` and `manifest.json` were retrieved and inspected:

- License text: CC0 1.0 Universal, covering models, textures, and images.
- Origin disclosure: procedural Blender-script model; no generative AI model directly produced geometry or textures.
- Manifest: 2,765,668-byte full GLB; 32,456 triangles; Base Color, Roughness, Metallic, and Normal maps at 2,048 px.
- The actual GLB binary could not be downloaded from this environment, so mesh and texture integrity remain untested. It is not included in this graybox deliverable.

Source page: https://grab3d.com/models/buildings/warehouse/  
License: https://grab3d.com/dl/warehouse/LICENSE.txt  
Manifest: https://grab3d.com/dl/warehouse/manifest.json

Other listings checked:
- Innerscene Godown Warehouse: CC0 claimed by the source page; 5.4 MB GLB; 30.5 × 22.25 × 8.4 m; download redirect inaccessible.
- 1DesignTool Warehouse Shell: custom license permits use in commercial games and modification, but prohibits redistribution of the raw model file or model packs; therefore it is not being copied into this public repository.

## Gate status

- G1 Requirements: documented; design brief remains DRAFT
- G2 Graybox: **WAITING FOR OWNER REVIEW**
- G3 Visual integration: NOT_TESTED
- G4 Performance: NOT_TESTED
- G5 Gameplay: NOT_TESTED
- G6 Release: NOT_TESTED

## Required owner decision

Review the untextured graybox and request geometry changes or approve this blockout. No further final material, texture, or lighting work should be performed until explicit owner approval is recorded.
