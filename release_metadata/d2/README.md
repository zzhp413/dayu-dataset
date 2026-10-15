# D2: Textured 3D Mesh Dataset

## Overview and acquisition

D2 was reconstructed from five-view oblique photogrammetry. It comprises multiple small-scale scenes with diverse land-cover types, including isolated buildings, connected buildings, building clusters, and grassland.

No additional preprocessing was performed for this release.

## Data contents

The supplied data contain five Wavefront OBJ mesh models, their MTL material files, and PNG texture images:

| Mesh file | Material file |
| --- | --- |
| `123.obj` | `123.obj.mtl` |
| `building_connected.obj` | `building_connected.obj.mtl` |
| `building_multi.obj` | `building_multi.obj.mtl` |
| `DSM.obj` | `DSM.obj.mtl` |
| `terrain.obj` | `terrain.obj.mtl` |

Texture images referenced by the material files are located alongside the OBJ and MTL files. Additional texture images are supplied in `texture_raw/`. The material files reference the images alongside the models; they do not automatically switch to the images in `texture_raw/`.

## Opening the models

1. Extract `D2.zip` while preserving its directory structure and filenames.
2. Open an OBJ file in a viewer that supports Wavefront OBJ, MTL materials, and image textures.
3. Keep the matching MTL file and its referenced PNG images beside the OBJ file. Moving or renaming those files may break texture loading.

## License and attribution

The D2 data are made available under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license:

https://creativecommons.org/licenses/by/4.0/

The full license text is provided in `LICENSE.txt`. Credit the dataset authors listed in the Figshare record, include the dataset DOI and license link, and indicate any changes you make. Retain any supplied copyright and attribution notices.

## Dataset record and citation

Figshare DOI: **10.6084/m9.figshare.34522161**

https://doi.org/10.6084/m9.figshare.34522161

Use the Figshare record's citation information for the author names, title, publication year, and version.

## File integrity

`SHA256SUMS.txt` contains SHA-256 hashes for the 250 data files inspected for this release. Paths in that file are relative to the extracted `d2/` data directory, the directory containing `123.obj`. The manifest covers the model, material, and texture files; it does not hash the ZIP archive or these accompanying documentation files.

When downloading the data, also download this README, `LICENSE.txt`, and `SHA256SUMS.txt` from the Figshare item.
