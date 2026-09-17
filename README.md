# FACC — Fully automatic cell counting

**Version 1.4.0 · Author: qianghw · Contact: qianghw@foxmail.com**

FACC is a local Windows application for fluorescence microscopy image analysis, automatic candidate counting, numbered annotation, and manual review. Its muscle-fiber workflow uses spectrin-defined boundaries to identify fiber candidates and supports DAPI-based internal-nucleus classification and dystrophin-positive membrane classification.

## Features

- Automatic counting, numbered annotations, interactive review, and editable `.facc` projects.
- Drag-and-drop image loading and batch analysis.
- Fluorescence measurements in candidate interiors and boundary bands.
- Central-nucleated fiber counts: a fiber with at least one qualifying internal nucleus is counted once, even when multiple nuclei are present.
- Dystrophin-positive fiber counts and proportions, with membrane signal thresholds and manual review.
- Saved default parameters, large-project loading with progress and cancellation, and improved export performance.

Automatic classifications are candidates for review. Dystrophin-positive fiber proportion describes fluorescence classification and does not directly measure functional recovery or normal protein abundance.

## Download and run

The published release is **[v1.4.0](https://github.com/BeichenSi/FACC/releases/tag/v1.4.0)**. Download its Windows x64 package, extract all files, and run `FACC.exe`; keep its `_internal` folder alongside it. The desktop interface is in Chinese. Python is not required for the packaged application.

## Source and documentation

The complete Python application, tests, build configuration, synthetic demonstrations, and third-party notices are included in [FACC_v1.4.0_Source.zip](FACC_v1.4.0_Source.zip). Extract this archive and read its README.md for supported image formats, analysis settings, exports, source installation, and build instructions. The development and packaging environment used Windows 11 x64 and Python 3.12.14.

See [Code Availability](CODE_AVAILABILITY.md) for manuscript text and [release checksums](RELEASE_CHECKSUMS.txt) for package verification. Biological microscopy images and analysis projects are not included in this repository.

## 中文说明

FACC 用于荧光切片候选计数、编号和人工复核，支持中央核肌纤维比例、dystrophin 阳性肌纤维比例，以及内部和边界周带荧光强度导出。请下载并解压 [完整源码包](FACC_v1.4.0_Source.zip)，其中包含 README.md、源码、测试及完整使用说明。v1.4.0 增加默认参数保存、优化大项目打开与导出速度，并修复参数箭头和界面排版问题。

## Licensing

This release does not declare a project-specific open-source license. Contact qianghw@foxmail.com regarding reuse or redistribution permissions. Third-party components retain their respective licenses; see THIRD_PARTY_NOTICES.md and ThirdPartyLicenses/ inside the source archive.
