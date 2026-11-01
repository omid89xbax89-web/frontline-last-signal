# Warehouse Graybox v001 — Geometry Review Submission

**Status:** DRAFT — WAITING FOR PROJECT OWNER REVIEW  
**Asset ID:** WAREHOUSE-001-GRAYBOX  
**Created:** 2026-11-01  
**Source:** Original procedural blockout generated for this project; it is not the Grab3D downloaded model.

## Deliverable

- Local review file: `FRONTLINE_WAREHOUSE_GRAYBOX_v001.glb`
- Preview: `FRONTLINE_WAREHOUSE_GRAYBOX_v001_preview.png`
- Front preview: `FRONTLINE_WAREHOUSE_GRAYBOX_v001_front.png`
- GLB size: 15,040 bytes
- GLB format: glTF Binary 2.0

## Structural validation performed

The exported GLB was re-opened with a glTF-capable mesh library after export.

- Geometry objects: 26
- Total triangles: 312
- Every mesh contains faces: yes
- Main warehouse body target dimensions: 44.0 × 39.3 × approximately 9.5 m
- The complete blockout includes a front loading platform and canopy, so its total bounding box is larger than the building shell.
- Geometry uses neutral gray surfaces only; no final textures or material design has been applied.

## Current geometry contents

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
- No collision mesh has been authored.
- No engine import, lighting, mobile performance, or gameplay test has been performed.
- The dimensions and silhouette need owner review before detail work.

## External free warehouse candidate

Grab3D's page currently advertises a separate warehouse model under CC0 1.0, with a full GLB listing of 32,456 triangles and 2K maps. However, direct retrieval from this working environment failed. The downloaded package's own `LICENSE.txt` and `manifest.json` have therefore not been inspected. The external model is not included in this deliverable.

Source page: https://grab3d.com/models/buildings/warehouse/  
API/download documentation: https://grab3d.com/developers/

## Required decision

Please review the untextured graybox and request geometry changes or approve this blockout. Do not start final materials, textures, or lighting until explicit owner approval is recorded.

## Current gate status

- G1 Requirements: documented, brief remains DRAFT
- G2 Graybox: **WAITING FOR OWNER REVIEW**
- G3 Visual integration: NOT_TESTED
- G4 Performance: NOT_TESTED
- G5 Gameplay: NOT_TESTED
- G6 Release: NOT_TESTED
