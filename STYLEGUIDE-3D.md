# 3D Style Guide Blender

- Units: metres. Apply scale before export.
- Axes: MSFS is Y up. Use exporter settings that match MSFS.
- Naming: aw139 part side lod, example aw139 doorL lod0.
- Pivots: set realistic origins for animated parts.
- LODs: LOD0 about 150k tris exterior. LOD1 about 60 percent. LOD2 about 20 percent.
- UVs: non overlapping where needed. Use trim sheets where possible.
- Materials: PBR, suffixes _albedo, _metallic, _normal.
- Animation: actions named anim part. Document in docs animations and rigging.md.
- Export: GLTF separate with BIN. Use tools export blender to gltf.ps1 for consistency.
