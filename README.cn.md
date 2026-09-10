# nfpm

[English version](./README.md)

nFPM is Not FPM - a simple deb, rpm, apk, ipk, and arch linux packager written in Go

![nfpm](https://repo.x-cmd.io/nfpm.svg?lang=zh)

## 安装

```sh
x install nfpm
```

## 代码规模

合计: **17,189** 行代码（覆盖前 5 种语言、共 **111** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 13,509 | 627 | 1,946 | 49 |
| Yaml | 1,303 | 17 | 44 | 49 |
| Json | 1,120 | 0 | 0 | 1 |
| Dockerfile | 765 | 106 | 165 | 11 |
| Svg | 265 | 0 | 0 | 1 |

## OpenSSF Scorecard 评分

总评分: **7.3 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/goreleaser/nfpm>
- **官网**: <https://nfpm.goreleaser.com/>
- **许可证**: MIT

## 发布

- **最新版本**: `v2.47.0` (2026-06-20)
- **最近提交**: 2026-09-10
- **Release 含资产**: 31 个

## 流行度

- **Star**: 2,635 · **Fork**: 191 · **开放 issue**: 233 · **贡献者**: 89

## 累计统计

- **发布数**: 163 · **已合并 PR**: 737 · **开放 PR**: 9 · **已关闭 issue**: 225 · **开放 issue**: 8 · **提交数**: 1308

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 7 | 2 | 0 | 0 | 10 |
| last60d | 2026-07-12 | 0 | 14 | 3 | 1 | 2 | 20 |
| 90d | 2026-06-12 | 1 | 27 | 4 | 3 | 2 | 43 |
| last180d | 2026-03-14 | 6 | 57 | 8 | 7 | 3 | 100 |
| 360d | 2025-09-15 | 14 | 115 | 8 | 19 | 4 | 194 |
| last720d | 2024-09-20 | 22 | 200 | 8 | 37 | 5 | 310 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [checksums.txt](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/checksums.txt) | 2.7 KiB | `other` |
| [checksums.txt.sigstore.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/checksums.txt.sigstore.json) | 9.9 KiB | `other` |
| [nfpm-2.47.0-1.aarch64.rpm](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm-2.47.0-1.aarch64.rpm) | 5.7 MiB | `runtime/rpm/aarch64` |
| [nfpm-2.47.0-1.ppc64le.rpm](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm-2.47.0-1.ppc64le.rpm) | 5.7 MiB | `runtime/rpm/ppc64le` |
| [nfpm-2.47.0-1.s390x.rpm](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm-2.47.0-1.s390x.rpm) | 6.1 MiB | `runtime/rpm/s390x` |
| [nfpm-2.47.0-1.x86_64.rpm](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm-2.47.0-1.x86_64.rpm) | 6.3 MiB | `runtime/rpm/x86_64` |
| [nfpm_2.47.0_aarch64.apk](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_aarch64.apk) | 5.9 MiB | `other` |
| [nfpm_2.47.0_amd64.deb](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_amd64.deb) | 6.3 MiB | `runtime/deb/amd64` |
| [nfpm_2.47.0_arm64.deb](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_arm64.deb) | 5.7 MiB | `runtime/deb/arm64` |
| [nfpm_2.47.0_Darwin_arm64.tar.gz](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Darwin_arm64.tar.gz) | 5.9 MiB | `native/darwin/arm64` |
| [nfpm_2.47.0_Darwin_arm64.tar.gz.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Darwin_arm64.tar.gz.sbom.json) | 119.7 KiB | `native/darwin/arm64` |
| [nfpm_2.47.0_Darwin_x86_64.tar.gz](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Darwin_x86_64.tar.gz) | 6.4 MiB | `native/darwin/x64` |
| [nfpm_2.47.0_Darwin_x86_64.tar.gz.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Darwin_x86_64.tar.gz.sbom.json) | 119.8 KiB | `native/darwin/x64` |
| [nfpm_2.47.0_Linux_arm64.tar.gz](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_arm64.tar.gz) | 5.7 MiB | `native/linux/arm64` |
| [nfpm_2.47.0_Linux_arm64.tar.gz.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_arm64.tar.gz.sbom.json) | 119.6 KiB | `native/linux/arm64` |
| [nfpm_2.47.0_Linux_ppc64le.tar.gz](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_ppc64le.tar.gz) | 5.7 MiB | `native/unknown` |
| [nfpm_2.47.0_Linux_ppc64le.tar.gz.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_ppc64le.tar.gz.sbom.json) | 118.3 KiB | `other` |
| [nfpm_2.47.0_Linux_s390x.tar.gz](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_s390x.tar.gz) | 6.1 MiB | `native/unknown` |
| [nfpm_2.47.0_Linux_s390x.tar.gz.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_s390x.tar.gz.sbom.json) | 118.1 KiB | `other` |
| [nfpm_2.47.0_Linux_x86_64.tar.gz](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_x86_64.tar.gz) | 6.3 MiB | `native/linux/x64` |
| [nfpm_2.47.0_Linux_x86_64.tar.gz.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Linux_x86_64.tar.gz.sbom.json) | 119.7 KiB | `native/linux/x64` |
| [nfpm_2.47.0_ppc64el.deb](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_ppc64el.deb) | 5.7 MiB | `runtime/deb/ppc64el` |
| [nfpm_2.47.0_ppc64le.apk](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_ppc64le.apk) | 5.9 MiB | `other` |
| [nfpm_2.47.0_s390x.apk](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_s390x.apk) | 6.3 MiB | `other` |
| [nfpm_2.47.0_s390x.deb](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_s390x.deb) | 6.1 MiB | `runtime/deb/s390x` |
| [nfpm_2.47.0_source.tar.gz](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_source.tar.gz) | 596.1 KiB | `native/unknown` |
| [nfpm_2.47.0_Windows_arm64.zip](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Windows_arm64.zip) | 5.8 MiB | `native/win/arm64` |
| [nfpm_2.47.0_Windows_arm64.zip.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Windows_arm64.zip.sbom.json) | 122.6 KiB | `native/win/arm64` |
| [nfpm_2.47.0_Windows_x86_64.zip](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Windows_x86_64.zip) | 6.5 MiB | `native/win/x64` |
| [nfpm_2.47.0_Windows_x86_64.zip.sbom.json](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_Windows_x86_64.zip.sbom.json) | 122.7 KiB | `native/win/x64` |
| [nfpm_2.47.0_x86_64.apk](https://github.com/goreleaser/nfpm/releases/download/v2.47.0/nfpm_2.47.0_x86_64.apk) | 6.5 MiB | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/nfpm) 上共有 **30** 个发行版报告此项目。**11** 个 ✅ 已是最新上游版本，**18** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `2.47.0` | ✅ latest |
| Nix unstable | `2.47.0` | ✅ latest |
| Alpine edge | `2.47.0` | ✅ latest |
| openSUSE Tumbleweed | `2.47.0` | ✅ latest |

## 改进这些数据

nfpm 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `nfpm` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/nfpm.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T20:53:55Z._
