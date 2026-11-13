# entrohub-landing

entrohub.io 首页，单页静态站（无构建）。

- 线上：https://entrohub.io （Vercel，entrohub 团队，项目 `entrohub-landing`）
- 源码取自线上 2026-11-13，与 Vercel 部署源码（Source 页）一致；`.vercelignore` 在 Vercel 里有，线上取不到，需要时再从控制台补。
- 文件：`index.html`、`llms.txt`、`robots.txt`、`sitemap.xml`、`assets/`
- 设计与决策笔记在 Yuli 的 Obsidian：`60_项目/Entrohub/网站/`、`80_设计/网站版式参考/`

## 改版流程

1. 在分支上改，推送后 Vercel 自动生成预览链接，给 Yuli 看。
2. Yuli 说「发」才合并到 main，main 自动部署到 entrohub.io。
3. 每场活动后更新：下一场的日期/主题/报名链接，JSON-LD 里的活动信息。
