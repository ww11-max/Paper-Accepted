# 版本与下载

安装包通过 GitHub Releases 发布。下载后请解压整包，不要只把 exe 拖出来。

| 版本 | 日期 | 安装包 | 说明 |
|---|---|---|---|
| v2026.10.31 | 2026-10-31 | [下载](https://github.com/ww11-max/Paper-Accepted/releases/tag/v2026.10.31) | [发布说明](releases/2026-10-31.md) |
| v2026.10.30b | 2026-10-30 | [下载](https://github.com/ww11-max/Paper-Accepted/releases/tag/v2026.10.30b) | [发布说明](releases/2026-10-30b.md) |
| v2026.10.30 | 2026-10-30 | [下载](https://github.com/ww11-max/Paper-Accepted/releases/tag/v2026.10.30) | [发布说明](releases/2026-10-30.md) |
| v2026.10.27b | 2026-10-27 | [下载](https://github.com/ww11-max/Paper-Accepted/releases/tag/v2026.10.27b) | [发布说明](releases/2026-10-27b.md) |

最新版本始终见 [Releases](https://github.com/ww11-max/Paper-Accepted/releases/latest)。

## 校验

每个安装包附对应的 `.sha256` 文件。下载后可校验：

```powershell
Get-FileHash .\PaperAccepted-win64-20261031.zip -Algorithm SHA256
```

将结果与 `releases/PaperAccepted-win64-20261031.zip.sha256` 中的值比对。