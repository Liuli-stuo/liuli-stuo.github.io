# 请遵守规则 · 互动文字游戏

## 线上入口

| 版本 | 链接 | 说明 |
| --- | --- | --- |
| 正式版 · 轻量 | https://liuli-stuo.github.io/ | 手机优先，加载最快 |
| 正式版 · 完整 | https://liuli-stuo.github.io/offline.html | 全部素材内嵌，文件较大 |
| 试玩版 · 轻量 | https://liuli-stuo.github.io/demo/ | 序章 + 第一夜，手机推荐 |
| 试玩版 · 完整 | https://liuli-stuo.github.io/demo/full.html | 序章 + 第一夜，素材完整 |

当前线上版本为 P0P2：污染消耗、投票表态与回调、三次弃权计数、路线锁定、HE 门槛 55、第 11 结局「镜中人」。

## 部署

由 GitHub Actions 的 `Sync game files` 工作流从构建产物同步到 `main` 分支，再由 GitHub Pages 发布。更新游戏时修改工作流中的四个构建下载地址，并更新 `sync.trigger` 触发同步。
