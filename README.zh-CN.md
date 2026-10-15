# 纹理三维网格数据集：D1、D2 与 D3

[English](README.md)

本仓库统一介绍 D1、D2、D3，并提供数据下载、许可、来源署名和使用说明。数据压缩包托管在 Figshare，仓库内保留说明文件和校验清单。

## 数据下载

三个公开数据条目均采用 **CC BY 4.0**。D3 下载仅包含下文说明的 Sketchfab 公开子集。

| 数据集 | 内容 | 数据 DOI | 下载压缩包 |
| --- | --- | --- | --- |
| **D1** | 约 0.2 km² 的大规模真实感城市三维场景，包含 20 个 OBJ 模型 | [10.6084/m9.figshare.34523802](https://doi.org/10.6084/m9.figshare.34523802) | [D1.zip](https://ndownloader.figshare.com/files/70166028) |
| **D2** | 独立建筑、相连建筑、建筑群和草地等小规模场景，包含 5 个 OBJ 模型 | [10.6084/m9.figshare.34522161](https://doi.org/10.6084/m9.figshare.34522161) | [D2.zip](https://ndownloader.figshare.com/files/70163982) |
| **D3 公开子集** | 来自 2 个 Sketchfab 原始模型的 6 个 OBJ 模型：1 个施工场地模型与 5 个街道分块 | [10.6084/m9.figshare.34524819](https://doi.org/10.6084/m9.figshare.34524819) | [D3_public.zip](https://ndownloader.figshare.com/files/70166994) |

压缩包链接对应 2026 年 10 月 15 日发布的第 1 版文件。无版本后缀的 DOI 指向最新公开版本；需要引用固定版本时，请使用 [CITATION.md](CITATION.md) 中带 `.v1` 的 DOI。

## 采集方式与处理

**D1、D2** 均通过五视倾斜摄影测量重建。D1 覆盖约 0.2 km²，使用 5 m × 5 m 瓦片进行空间划分；D2 包含多种地表覆盖类型的小规模场景。公开发布时未进行额外预处理。

**D3 公开子集** 的来源及处理如下，两个原始模型均为 CC BY 4.0：

| 原始模型 | 原作者 | 对应目录 | 处理说明 |
| --- | --- | --- | --- |
| [Construction site, building site, architecture](https://sketchfab.com/3d-models/construction-site-building-site-architecture-62fc443a7d91465f844de1cf95731f60) | [Metazeon](https://sketchfab.com/Metazeon) | `20250408_004_OUTPUT_LOD04/` | 未报告额外处理 |
| [Small Canadian Street Experiment Photogrammetry](https://sketchfab.com/3d-models/small-canadian-street-experiment-photogrammetry-1bdfb91607ea4310a4bebdbf167714c7) | [Air Digital](https://sketchfab.com/AirDigitalca) | `fullstree_1/` 至 `fullstree_5/` | 使用 MeshLab 将同一原始模型分为五部分 |

完整实验 D3 还包含来自 Google 的城市场景。`berlin`、`los_angeles`、`paris` 和 `sydney` 四个目录的数据**未包含在公开数据包或本仓库内**。公开子集的统计信息不代表完整实验 D3 的统计信息。

## 如何使用

1. 从上表下载所需数据集。
2. 解压时保留原始目录结构和文件名。
3. 使用支持 OBJ、MTL 和图像纹理的软件打开 OBJ 文件。
4. 保持材质及纹理文件的位置，避免破坏纹理引用。

D1、D2 的 README、许可证和校验清单需从相应 Figshare 条目一并下载。D3 压缩包已包含说明、许可证、第三方署名、来源元数据及校验清单。

## 配套文档

| 数据集 | 使用说明 | 许可证 | 数据校验清单 |
| --- | --- | --- | --- |
| D1 | [README](release_metadata/d1/README.md) | [CC BY 4.0](release_metadata/d1/LICENSE.txt) | [SHA-256](release_metadata/d1/SHA256SUMS.txt) |
| D2 | [README](release_metadata/d2/README.md) | [CC BY 4.0](release_metadata/d2/LICENSE.txt) | [SHA-256](release_metadata/d2/SHA256SUMS.txt) |
| D3 公开子集 | [README](release_metadata/d3/README.md) | [CC BY 4.0](release_metadata/d3/LICENSE.txt) | [SHA-256](release_metadata/d3/SHA256SUMS.txt) |

D1、D2 校验清单的路径以各自解压后的数据目录为基准。D3 校验清单的路径以 `D3_public/` 为基准，包含数据及包内配套说明文件。

## 许可与署名

本仓库说明文档使用 [CC BY 4.0](LICENSE.txt)。各数据集的具体许可及署名要求见各自说明。

D1、D2 作者信息以 Figshare 记录为准。使用 D3 时，须保留原作者 **Metazeon**、**Air Digital** 的署名、来源链接、许可链接及处理说明，详见 [第三方署名文件](release_metadata/d3/THIRD_PARTY_NOTICES.md)。仅引用 Figshare 汇编条目不能替代原模型署名。

已公开数据和文档的 CC BY 4.0 许可不授予任何被排除的 Google 来源数据的使用或再分发权。

## 引用

请引用实际使用的 Figshare 数据集，固定版本的引用信息见 [CITATION.md](CITATION.md)。D3 还需保留原始模型署名。
