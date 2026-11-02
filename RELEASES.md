# 版本与下载

安装包通过 GitHub Releases 发布。下载后请解压整包，不要只把 exe 拖出来。

| 版本 | 日期 | 安装包 | 说明 |
|---|---|---|---|
| v2026.11.02 | 2026-11-02 | [下载](https://github.com/ww11-max/Paper-Accepted/releases/tag/v2026.11.02) | [发布说明](releases/2026-11-02.md) |
| v2026.10.27b ~ v2026.10.31 | 2026-10-27 ~ 10-31 | 已下线，不再提供下载 | 含已知安全问题，请勿使用 |

最新版本始终见 [Releases](https://github.com/ww11-max/Paper-Accepted/releases/latest)。

> **提示**：2026-11-02 之前的安装包已全部从仓库移除。若你手上仍留有旧版，请删除并改用最新版。

## 校验

每个安装包附对应的 `.sha256` 文件。下载后可校验：

```powershell
Get-FileHash .\PaperAccepted-win64-20261102.zip -Algorithm SHA256
```

将结果与 `releases/PaperAccepted-win64-20261102.zip.sha256` 中的值比对。
