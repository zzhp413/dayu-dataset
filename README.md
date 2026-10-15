# Textured 3D Mesh Datasets: D1 and D2

[中文说明](README.zh-CN.md)

This repository is the shared documentation and download entry point for two textured 3D mesh datasets, D1 and D2. The data archives are hosted on Figshare; the repository contains dataset descriptions, licenses, and checksum manifests.

## Download

Both datasets are publicly available under **CC BY 4.0**.

| Dataset | Contents | Dataset DOI | Archive |
| --- | --- | --- | --- |
| **D1** | Large-scale photorealistic urban scene, approximately 0.2 km²; 20 OBJ models | [10.6084/m9.figshare.34523802](https://doi.org/10.6084/m9.figshare.34523802) | [D1.zip](https://ndownloader.figshare.com/files/70166028) |
| **D2** | Small-scale scenes with isolated buildings, connected buildings, building clusters, and grassland; 5 OBJ models | [10.6084/m9.figshare.34522161](https://doi.org/10.6084/m9.figshare.34522161) | [D2.zip](https://ndownloader.figshare.com/files/70163982) |

The archive links refer to the files published in version 1 on 2026-10-15. The base DOI links lead to the latest public versions. Use the version-specific DOIs in [CITATION.md](CITATION.md) to cite a fixed release.

## Acquisition and processing

**D1 and D2** were reconstructed from five-view oblique photogrammetry. D1 covers approximately 0.2 km² and was spatially partitioned using 5 m × 5 m tiles. D2 comprises multiple small-scale scenes with diverse land-cover types. No additional preprocessing was performed for these public releases.

## Using the data

1. Download the archive for the required dataset from the table above.
2. Extract it while preserving filenames and directory structure.
3. Open an OBJ file in a viewer that supports OBJ meshes, MTL materials, and image textures.
4. Keep material and texture files in their original locations so the models can resolve their texture references.

Download the accompanying `README.md`, `LICENSE.txt`, and `SHA256SUMS.txt` from each Figshare record as well.

## Dataset documentation

| Dataset | Usage notes | License | Data checksums |
| --- | --- | --- | --- |
| D1 | [README](release_metadata/d1/README.md) | [CC BY 4.0](release_metadata/d1/LICENSE.txt) | [SHA-256 manifest](release_metadata/d1/SHA256SUMS.txt) |
| D2 | [README](release_metadata/d2/README.md) | [CC BY 4.0](release_metadata/d2/LICENSE.txt) | [SHA-256 manifest](release_metadata/d2/SHA256SUMS.txt) |

D1 and D2 checksum paths are relative to their extracted data directories.

## License and attribution

The repository documentation is provided under [CC BY 4.0](LICENSE.txt). Dataset-specific license and attribution requirements are described in the linked documents above.

D1 and D2 authorship follows their Figshare records. Retain the supplied attribution and license information, and indicate any changes you make.

## Citation

Please cite the individual Figshare datasets used in your work, using the [version 1 citations](CITATION.md). Repository documentation does not replace the datasets' DOI records.
