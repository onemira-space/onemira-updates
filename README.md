# onemira-updates

OneMira 桌面应用的更新源（公开）。

- `mira-context/appcast.xml` — Sparkle 更新清单，经 GitHub Pages 以 `https://updates.onemira.com/mira-context/appcast.xml` 提供。
- `mira-context/windows/stable.json` — Tauri v2 Windows 稳定通道清单，经 GitHub Pages 以 `https://updates.onemira.com/mira-context/windows/stable.json` 提供。
- 更新 zip 包作为本仓库 **Releases** 的附件上传，URL 形如
  `https://github.com/onemira-space/onemira-updates/releases/download/<tag>/OneMira-<ver>.zip`。
- Windows NSIS 安装包及其 `.sig` 也作为 Release 附件上传；清单中的
  `windows-x86_64.signature` 是 `.sig` 文件的完整内容。

源码不在此仓库（私有 `onemira-space/mira-context`）。
