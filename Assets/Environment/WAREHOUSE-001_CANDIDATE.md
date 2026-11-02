# Warehouse Asset Candidate — WAREHOUSE-001

**Status:** SOURCE LICENSE VERIFIED; SOURCE BINARY DOWNLOAD BLOCKED; LOCAL GRAYBOX AVAILABLE; OWNER REVIEW PENDING  
**Project:** FRONTLINE: LAST SIGNAL  
**Review date:** 2026-11-02

## Primary candidate — Grab3D Warehouse

- Model page: https://grab3d.com/models/buildings/warehouse/
- API and download documentation: https://grab3d.com/developers/
- Listed file: `warehouse.glb`
- Full GLB: 2,765,668 bytes; listed as 2.6 MB
- Light GLB: 1,410,864 bytes; listed as 1.3 MB
- Full geometry: 32,456 triangles
- Light geometry: 17,378 triangles
- Dimensions: 44.000 × 39.300 × 9.540 m (W × D × H)
- Full texture resolution: 2,048 px; light: 1,024 px
- Manifest-listed PBR maps: Base Color, Roughness, Metallic, Normal
- Contents: exterior industrial hall, loading dock, roller doors, roof light strips and marked yard
- Limitation: closed exterior only; no interior, brand, or text. Manifest says front faces -Y and identifies a movable ground-level roller door.

### License and origin evidence

The package's own `LICENSE.txt` was retrieved as text. It states **CC0 1.0 Universal** and explicitly covers the 3D models, textures, and images. Its origin disclosure says the asset was built procedurally with Blender scripts; no generative AI model produced the geometry or textures directly, although an AI coding assistant helped write the scripts.

The package's own `manifest.json` was also retrieved as text. It records `license: CC0-1.0`, the dimensions, triangle counts, texture maps, file sizes, and origin disclosure.

Evidence:
- Model page: https://grab3d.com/models/buildings/warehouse/
- Package license: https://grab3d.com/dl/warehouse/LICENSE.txt
- Package manifest: https://grab3d.com/dl/warehouse/manifest.json

### Download and validation status

The actual GLB download was attempted through the browser download link and the working download environment. The browser could not consume the binary response, and direct download attempts failed because the working environment could not resolve the external host. Therefore:

- Package-level license and manifest text: **RETRIEVED**
- Actual GLB bytes: **NOT DOWNLOADED**
- GLB integrity, mesh, normals, UVs, texture embedding, and hierarchy: **NOT TESTED**
- Engine import and runtime performance: **NOT_TESTED**

Do not describe the Grab3D GLB as downloaded, locally validated, or ready to import.

## Secondary candidate — Innerscene Godown Warehouse

- Source page: https://www.innerscene.com/tools/library/3d-parts/godown-warehouse-30-x-20-m-with-loading-dock-3d-model-c8599c4b
- Listing format/size: GLB, 5.4 MB
- Listed dimensions: 30.500 × 22.250 × 8.400 m
- Listing states the model is original and released under **CC0**, and describes it as a real-scale GLB with materials.
- The page does not provide a triangle count or a texture-map inventory.
- Download link redirected to a file host that was inaccessible from this environment; no binary validation was performed.

## Secondary candidate — 1DesignTool Warehouse Shell

- Source page: https://1designtool.com/3d/models/warehouse-and-logistics-warehouse-shell
- License: https://1designtool.com/3d/license
- Listed GLB: 456 KB; 4,524 triangles; 13,572 vertices; 32 meshes and 32 materials; static; no animation clip.
- Overall listed size: 48 × 10 × 35 m (W × H × D). The page separately describes the shed body as 36 × 24 × 10 m and the forecourt/apron as part of the larger overall footprint.
- The license permits personal and commercial use, modification, and shipping the model inside a compiled game without attribution. It prohibits redistributing the model file on its own or as an asset pack, uploading it to another marketplace, or claiming authorship.
- This is a potentially usable commercial-game asset only if the redistribution restrictions are respected. It is not CC0 and must not be copied as a raw model into this public repository.
- The GLB download was not locally validated in this run.

## Project-local graybox

A separate original procedural blockout already exists locally and is **not a conversion of the Grab3D download**:

- File: `FRONTLINE_WAREHOUSE_GRAYBOX_v001.glb`
- Format: glTF Binary 2.0
- Size: 15,040 bytes
- Geometry: 26 objects, 312 triangles
- Overall bounds: 44.000 × 44.225 × 9.510 m
- Materials/textures: none; 0 images, 0 textures, 0 materials
- Includes wall masses, three loading-bay openings, roof slab/edges, loading platform, simple bumpers, canopy, and support posts.
- Status: structural file-load check passed; geometry review remains **WAITING FOR OWNER REVIEW**.
- It is a first-pass graybox, not a detailed or production-ready architectural asset.

The graybox is kept separate from the unverified external binaries. No paid credits, subscription, or purchase was used.

## Required next steps

1. Review the project-local untextured graybox and request geometry revisions or approve it.
2. If the external Grab3D asset is still preferred, obtain its GLB through a working download path and validate the actual binary before selecting it.
3. Do not perform additional final material, texture, or lighting work until the owner has approved the geometry stage.
4. After approval, record the decision and proceed to the next asset-pipeline gate.

## Current verification result

**A CC0 candidate has been found and its package license/manifest text verified, but the candidate GLB itself could not be downloaded or tested. A separate original untextured graybox is available for owner review. No external binary is represented as locally validated.**
