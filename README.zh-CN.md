# 纹理三维网格数据集：D1 与 D2

[English](README.md)

本仓库统一介绍 D1、D2，并提供数据下载、许可和使用说明。数据压缩包托管在 Figshare，仓库内保留说明文件和校验清单。

## 数据下载

两个公开数据条目均采用 **CC BY 4.0**。

| 数据集 | 内容 | 数据 DOI | 下载压缩包 |
| --- | --- | --- | --- |
| **D1** | 约 0.2 km² 的大规模真实感城市三维场景，包含 20 个 OBJ 模型 | [10.6084/m9.figshare.34523802](https://doi.org/10.6084/m9.figshare.34523802) | [D1.zip](https://ndownloader.figshare.com/files/70166028) |
| **D2** | 独立建筑、相连建筑、建筑群和草地等小规模场景，包含 5 个 OBJ 模型 | [10.6084/m9.figshare.34522161](https://doi.org/10.6084/m9.figshare.34522161) | [D2.zip](https://ndownloader.figshare.com/files/70163982) |

压缩包链接对应 2026 年 10 月 15 日发布的第 1 版文件。无版本后缀的 DOI 指向最新公开版本；需要引用固定版本时，请使用 [CITATION.md](CITATION.md) 中带 `.v1` 的 DOI。

## 采集方式与处理

**D1、D2** 均通过五视倾斜摄影测量重建。D1 覆盖约 0.2 km²，使用 5 m × 5 m 瓦片进行空间划分；D2 包含多种地表覆盖类型的小规模场景。公开发布时未进行额外预处理。

## 如何使用

1. 从上表下载所需数据集。
2. 解压时保留原始目录结构和文件名。
3. 使用支持 OBJ、MTL 和图像纹理的软件打开 OBJ 文件。
4. 保持材质及纹理文件的位置，避免破坏纹理引用。

请从相应 Figshare 条目一并下载 README、许可证和校验清单。

## 配套文档

| 数据集 | 使用说明 | 许可证 | 数据校验清单 |
| --- | --- | --- | --- |
| D1 | [README](release_metadata/d1/README.md) | [CC BY 4.0](release_metadata/d1/LICENSE.txt) | [SHA-256](release_metadata/d1/SHA256SUMS.txt) |
| D2 | [README](release_metadata/d2/README.md) | [CC BY 4.0](release_metadata/d2/LICENSE.txt) | [SHA-256](release_metadata/d2/SHA256SUMS.txt) |

D1、D2 校验清单的路径以各自解压后的数据目录为基准。

## 许可与署名

本仓库说明文档使用 [CC BY 4.0](LICENSE.txt)。各数据集的具体许可及署名要求见各自说明。

D1、D2 作者信息以 Figshare 记录为准。使用数据时请保留署名和许可信息，并注明你进行的修改。

## 引用

请引用实际使用的 Figshare 数据集，固定版本的引用信息见 [CITATION.md](CITATION.md)。
