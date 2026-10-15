# D3: Sketchfab-derived Textured 3D Models (Public Subset)

## Scope and acquisition

This release contains the Sketchfab-derived portion of D3: one construction-site model and five spatial parts of one street model. The six OBJ files originate from two source models, rather than six independently acquired scenes.

The full experimental D3 dataset also includes Google-sourced city scenes. The `berlin`, `los_angeles`, `paris`, and `sydney` directories are excluded from this public release. This Figshare item therefore represents the public subset of D3, not the complete experimental dataset.

The models were obtained from the source pages listed below.

## Sources and processing

| Release directory | Original model | Original creator | Processing |
| --- | --- | --- | --- |
| `20250408_004_OUTPUT_LOD04/` | [Construction site, building site, architecture](https://sketchfab.com/3d-models/construction-site-building-site-architecture-62fc443a7d91465f844de1cf95731f60) | [Metazeon](https://sketchfab.com/Metazeon) | No additional processing was reported for this release. |
| `fullstree_1/` through `fullstree_5/` | [Small Canadian Street Experiment Photogrammetry](https://sketchfab.com/3d-models/small-canadian-street-experiment-photogrammetry-1bdfb91607ea4310a4bebdbf167714c7) | [Air Digital](https://sketchfab.com/AirDigitalca) | The original model was partitioned into five parts using MeshLab. |

Both original models are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**, as checked using the official Sketchfab API on 2026-10-15. See `THIRD_PARTY_NOTICES.md` for the attribution statements and `SOURCE_METADATA.json` for the source metadata recorded at verification time.

The available processing record does not specify the MeshLab version or partitioning parameters. No additional model processing was reported beyond the street-model partitioning described above.

## Data contents

The data comprise six OBJ meshes, six MTL material files, and six texture image files (one PNG and five JPEG files), for a total of 18 data files. Each street part includes its own copy of the associated JPEG texture so that its directory can be used independently.

```text
D3_public/
  README.md
  LICENSE.txt
  THIRD_PARTY_NOTICES.md
  SOURCE_METADATA.json
  SHA256SUMS.txt
  20250408_004_OUTPUT_LOD04/
    20250408_004_RC_LOD04.obj
    20250408_004_RC_LOD0.mtl
    20250408_004_RC_LOD0_u0_v0_diffuse.png
  fullstree_1/
    fullstree_1.obj
    fullstree_1.obj.mtl
    fullstreedemo.jpg
  ... fullstree_2/ through fullstree_5/ ...
```

## Opening the models

Extract `D3_public.zip` while preserving its directory structure and filenames. Open an OBJ file in a viewer that supports Wavefront OBJ, MTL materials, and image textures. Keep each model's MTL and referenced texture files in their original locations.

## License and attribution

The original models and the distributed street-model parts are provided under **CC BY 4.0**:

https://creativecommons.org/licenses/by/4.0/

The full license text is in `LICENSE.txt`. Credit Metazeon and Air Digital for their respective models, link to the source pages and license, and indicate the MeshLab partitioning of the street model and any subsequent changes you make. Retain the supplied attribution notices. Citing only the Figshare compilation does not replace attribution to the original creators.

The compilation and documentation do not claim ownership of the underlying third-party models. No endorsement by either original creator is implied.

## Dataset citation

Figshare DOI: **10.6084/m9.figshare.34524819**

https://doi.org/10.6084/m9.figshare.34524819

Use the accompanying Figshare item's citation information for the compilation's authors, title, DOI, publication year, and version. Also retain the original-model attributions in `THIRD_PARTY_NOTICES.md`.

## File integrity

`SHA256SUMS.txt` lists SHA-256 hashes for the 18 data files and four accompanying documentation files (`README.md`, `LICENSE.txt`, `THIRD_PARTY_NOTICES.md`, and `SOURCE_METADATA.json`). Paths are relative to the extracted `D3_public/` directory. The manifest does not hash itself or the ZIP archive.
