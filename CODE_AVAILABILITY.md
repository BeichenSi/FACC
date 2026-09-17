# Code Availability

## Manuscript text — publication draft

FACC (Fully automatic cell counting), version 1.4.0, was developed by qianghw for the analysis and manual review of fluorescence microscopy images. The Python source code, analysis documentation, tests, and synthetic demonstration images are provided in the GitHub repository at https://github.com/BeichenSi/FACC. The software supports spectrin-based muscle-fiber candidate counting and annotation, DAPI-based classification of fibers containing at least one internal nucleus, dystrophin-positive fiber classification, and fluorescence intensity measurements in fiber interiors and boundary bands. The Windows x64 application is distributed through the repository's release page. Analysis parameters and review decisions can be saved in `.facc` project files to support reproducibility. The biological images used during local validation are not included in the code repository. Questions about the software or permission to reuse or redistribute the code should be addressed to qianghw (qianghw@foxmail.com).

**Publication check:** Confirm that the repository and v1.4.0 downloadable release are publicly accessible before using the paragraph above in a manuscript. No archival DOI has been assigned in this document. This release does not declare a project-specific open-source license; it should not be described as licensed open-source software unless a license is subsequently added by the author.

## 中文对照

FACC（Fully automatic cell counting，版本 1.4.0）由 qianghw 开发，用于荧光显微图像的分析和人工复核。Python 源码、分析说明、测试和合成演示图位于 GitHub 仓库 https://github.com/BeichenSi/FACC。软件支持基于血影蛋白的肌纤维候选计数与编号、基于 DAPI 的含至少一个内部核的肌纤维分类、dystrophin 阳性肌纤维分类，以及肌纤维内部和边界周带的荧光强度测量。Windows x64 程序通过仓库发布页面提供。分析参数和人工复核结果可保存在 `.facc` 项目中，以支持结果复现。代码仓库不包含本地验证使用的生物学图像。有关软件使用或源码再利用、再分发许可的问题，请联系 qianghw（qianghw@foxmail.com）。

## Reproducibility information

- Software version: 1.4.0.
- Author and contact: qianghw, qianghw@foxmail.com.
- Build environment: Windows 11 x64, Python 3.12.14.
- Source installation and dependency details: `source/README.md`, `source/requirements.txt`, and `source/pyproject.toml`.
- Package SHA-256 values: `RELEASE_CHECKSUMS.txt`.
- Retain the analyzed image, `.facc` project, exported parameters, and manual review decisions for each analysis.

An internal-nucleus classification counts each qualifying fiber once, regardless of the number of internal nuclei. A dystrophin-positive fiber proportion is an image-based classification; it is not a direct measurement of normal dystrophin abundance or functional recovery.
