# 葡萄输入法安装包发布

此仓库仅用于发布葡萄输入法安装包和二进制（GitHub Releases）。

源代码位于私有仓库 `putao520/gsc-srf`，不随本发布仓库公开。

## 下载

前往 [Releases](https://github.com/putao520/grape-ime-release/releases) 下载最新版安装包。

## 二进制与第三方许可

葡萄输入法是**混合许可的闭源二进制发行物**：

- 自有闭源部分的额外使用/再分发授权见 [LICENSE](./LICENSE)；
- 第三方开源库、运行时和模型继续适用各自原始许可，见
  [THIRD-PARTY-NOTICES.md](./THIRD-PARTY-NOTICES.md)；
- NVIDIA Sortformer 的要求见 [NVIDIA-NOTICE.txt](./NVIDIA-NOTICE.txt)；
- 官方安装包内部还包含 release-specific 的完整 `licenses` 目录和
  Rust 依赖许可证清单。

允许个人和商业使用，也允许镜像、托管和再分发未经修改的官方安装包。
这些额外条款不会缩小 MIT、Apache-2.0、NVIDIA Open Model License 或
其他第三方许可证独立授予的权利。
