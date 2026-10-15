# Textured 3D Mesh Datasets: D1, D2, and D3

[中文说明](README.zh-CN.md)

This repository is the shared documentation and download entry point for three textured 3D mesh datasets. The data archives are hosted on Figshare; the repository contains dataset descriptions, licenses, attribution notices, and checksum manifests.

## Download

All three datasets are publicly available under **CC BY 4.0**. The D3 download contains the public Sketchfab subset described below.

| Dataset | Contents | Dataset DOI | Archive |
| --- | --- | --- | --- |
| **D1** | Large-scale photorealistic urban scene, approximately 0.2 km²; 20 OBJ models | [10.6084/m9.figshare.34523802](https://doi.org/10.6084/m9.figshare.34523802) | [D1.zip](https://ndownloader.figshare.com/files/70166028) |
| **D2** | Small-scale scenes with isolated buildings, connected buildings, building clusters, and grassland; 5 OBJ models | [10.6084/m9.figshare.34522161](https://doi.org/10.6084/m9.figshare.34522161) | [D2.zip](https://ndownloader.figshare.com/files/70163982) |
| **D3 — public subset** | 6 OBJ models derived from 2 Sketchfab source models: one construction-site model and five street-model parts | [10.6084/m9.figshare.34524819](https://doi.org/10.6084/m9.figshare.34524819) | [D3_public.zip](https://ndownloader.figshare.com/files/70166994) |

The archive links refer to the files published in version 1 on 2026-10-15. The base DOI links lead to the latest public versions. Use the version-specific DOIs in [CITATION.md](CITATION.md) to cite a fixed release.

## Acquisition and processing

**D1 and D2** were reconstructed from five-view oblique photogrammetry. D1 covers approximately 0.2 km² and was spatially partitioned using 5 m × 5 m tiles. D2 comprises multiple small-scale scenes with diverse land-cover types. No additional preprocessing was performed for these public releases.

**D3** combines models obtained from other sources. This public release redistributes the following Sketchfab models under their original CC BY 4.0 licenses:

| Source model | Original creator | Distributed directories | Processing |
| --- | --- | --- | --- |
| [Construction site, building site, architecture](https://sketchfab.com/3d-models/construction-site-building-site-architecture-62fc443a7d91465f844de1cf95731f60) | [Metazeon](https://sketchfab.com/Metazeon) | `20250408_004_OUTPUT_LOD04/` | No additional processing |
| [Small Canadian Street Experiment Photogrammetry](https://sketchfab.com/3d-models/small-canadian-street-experiment-photogrammetry-1bdfb91607ea4310a4bebdbf167714c7) | [Air Digital](https://sketchfab.com/AirDigitalca) | `fullstree_1/` through `fullstree_5/` | Partitioned into five parts using MeshLab |

The full experimental D3 dataset also includes Google-sourced city scenes. The `berlin`, `los_angeles`, `paris`, and `sydney` data are **excluded from this public release and this repository**. The Figshare public subset contains no data from those four directories. Its statistics describe the public subset, rather than the complete experimental D3 dataset.

## Using the data

1. Download the archive for the required dataset from the table above.
2. Extract it while preserving filenames and directory structure.
3. Open an OBJ file in a viewer that supports OBJ meshes, MTL materials, and image textures.
4. Keep material and texture files in their original locations so the models can resolve their texture references.

For D1 and D2, download the accompanying `README.md`, `LICENSE.txt`, and `SHA256SUMS.txt` from the Figshare record as well. D3 includes these documents, its third-party notices, and recorded source metadata inside the archive.

## Dataset documentation

| Dataset | Usage notes | License | Data checksums |
| --- | --- | --- | --- |
| D1 | [README](release_metadata/d1/README.md) | [CC BY 4.0](release_metadata/d1/LICENSE.txt) | [SHA-256 manifest](release_metadata/d1/SHA256SUMS.txt) |
| D2 | [README](release_metadata/d2/README.md) | [CC BY 4.0](release_metadata/d2/LICENSE.txt) | [SHA-256 manifest](release_metadata/d2/SHA256SUMS.txt) |
| D3 public subset | [README](release_metadata/d3/README.md) | [CC BY 4.0](release_metadata/d3/LICENSE.txt) | [SHA-256 manifest](release_metadata/d3/SHA256SUMS.txt) |

D1 and D2 checksum paths are relative to their extracted data directories. D3 checksum paths are relative to the extracted `D3_public/` directory and cover its data and accompanying documentation.

## License and attribution

The repository documentation is provided under [CC BY 4.0](LICENSE.txt). Dataset-specific license and attribution requirements are described in the linked documents above.

D1 and D2 authorship follows their Figshare records. The original D3 models remain attributed to **Metazeon** and **Air Digital**; citing the dataset compilation does not replace these original-model credits. Retain [D3's third-party notices](release_metadata/d3/THIRD_PARTY_NOTICES.md), the source links, the license link, and the processing statements when redistributing those models.

The CC BY 4.0 licenses for the released data and documentation do not grant rights to the excluded Google-sourced content.

## Citation

Please cite the individual Figshare datasets used in your work, using the [version 1 citations](CITATION.md), and retain original-model attribution for D3. Repository documentation does not replace the datasets' DOI records.
