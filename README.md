# FDR-Catalog

F.D.R 游戏下载工具的自维护游戏目录源（公开数据仓库）。

**本仓库内容由 [fdr-catalog-pipeline](https://github.com/riesaexe/FDR) 定时自动生成与推送，请勿手改。**

- games.enc — AES-GCM 加密目录（FDRE magic），含游戏元数据（名称/分类/大小/版本/开发商/发售日/支持语种/评分/下载链接/提取码）
- 客户端 ackend/py_modules/custom_catalog.py 运行时拉取解密（gh-proxy 镜像优先 + 直连兜底）
- 明文只存在于私有侧，本仓库仅加密产物
