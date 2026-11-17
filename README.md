# AiBotSpace/.github

AiBotSpace 的 GitHub 主页配置仓库。

## 内容

| 路径 | 说明 |
| --- | --- |
| `profile/README.md` | 主页展示内容，渲染于 https://github.com/AiBotSpace |
| `.github/workflows/snake.yml` | 每天生成贡献贪吃蛇动画，推送到 `output` 分支 |

## 更新主页

编辑 `profile/README.md` 后推送到 `main` 分支即可生效。

## 贪吃蛇

工作流每天 UTC 00:00 运行一次，推送工作流文件本身时也会触发一次，也可在 Actions 页面手动触发（workflow_dispatch）。生成的 SVG 位于 `output` 分支，`profile/README.md` 通过 `raw.githubusercontent.com` 引用深色/浅色两版。
