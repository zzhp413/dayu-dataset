# D1: Large-Scale Photorealistic Urban 3D Dataset

## Overview and acquisition

D1 was reconstructed from five-view oblique photogrammetry. It is a large-scale photorealistic 3D urban scene covering approximately 0.2 km². The scene was spatially partitioned using 5 m × 5 m tiles.

No additional preprocessing was performed for this release.

## Data contents

The supplied data contain 20 Wavefront OBJ mesh models, 20 MTL material files, and 5,170 JPEG texture images, arranged in 20 scene subdirectories. The complete data directory contains 5,210 files.

Each scene subdirectory contains an OBJ model, its referenced MTL file, and texture images. For example:

```text
d1/
  Tile_X0_Y0_noNoise/
    merged_Tile_X0_Y0.obj
    merged_Tile_X0_Y0.obj.mtl
    ... JPEG texture images ...
  ... other scene subdirectories ...
```

## Opening the models

1. Extract `D1.zip` while preserving its directory structure and filenames.
2. Open an OBJ file from a scene subdirectory in a viewer that supports Wavefront OBJ, MTL materials, and image textures.
3. Keep the matching MTL file and its referenced JPEG images in their original locations. Moving or renaming those files may break texture loading.

## License and attribution

The D1 data are made available under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license:

https://creativecommons.org/licenses/by/4.0/

The full license text is provided in `LICENSE.txt`. Credit the dataset authors listed in the Figshare record, include the dataset DOI and license link, and indicate any changes you make. Retain any supplied copyright and attribution notices.

## Dataset record and citation

Figshare DOI: **10.6084/m9.figshare.34523802**

https://doi.org/10.6084/m9.figshare.34523802

Use the Figshare record's citation information for the author names, title, publication year, and version.

## File integrity

`SHA256SUMS.txt` contains SHA-256 hashes for the 5,210 data files inspected for this release. Paths in that file are relative to the extracted `d1/` data directory, the directory containing the `Tile_X0_Y0_noNoise/` subdirectory. The manifest covers the model, material, and texture files; it does not hash the ZIP archive or these accompanying documentation files.

When downloading the data, also download this README, `LICENSE.txt`, and `SHA256SUMS.txt` from the Figshare item.
