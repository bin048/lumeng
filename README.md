# lumeng
# lumeng
# Lumeng — 待办事项静态页面

这是一个简单的静态待办事项应用（单文件 HTML），支持：

- 新增 / 完成 / 删除待办
- 设置优先级与截止日期
- 拖拽或选择上传图片 / 文件（以 data URL 保存在 localStorage）
- 图片预览与文件下载

如何启用 GitHub Pages
1. 在仓库页面点击 Settings → Pages → Source，选择 "Deploy from a branch"，选择 `main` 分支和 `/ (root)` 目录，然后保存。
2. 等待几分钟后访问：`https://bin048.github.io/lumeng/`

自动部署
仓库包含一个 GitHub Actions workflow（.github/workflows/pages.yml），会在每次 push 到 main 时自动上传并部署 Pages。

注意事项
- 本示例将用户上传的文件以 data URL 的形式保存在 localStorage，长期使用会占用浏览器存储配额；建议用于演示/小规模使用，生产环境请把文件上传到后端或云存储并保存链接。
- 如果你希望我把截图添加到 README，我可以生成并上传截图（需要你确认）。
- 
