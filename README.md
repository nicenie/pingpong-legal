# Ping Pong Score — legal pages

App Store 要求的两个公开页面，托管于 GitHub Pages：

- `privacy.html` — 隐私政策（简中 / 繁中 / 英 / 日 / 俄）
- `support.html` — 支持与常见问题（同上五语）

**这个仓库是生成物，不要直接改。** 单一事实源在 App 仓库
`PingPongScore/docs/legal/`，改完跑：

```bash
bash docs/appstore/sync-legal.sh
```

页面无外部依赖（无字体、无脚本 CDN），深色模式自适应。
