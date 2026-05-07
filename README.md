# AI 导航站

> 基于 Vue 3 + Vite + Tailwind CSS 3 + Vue Router 4 构建的 AI 工具导航网站

## 项目简介

精心收录 600+ AI 工具，涵盖聊天对话、图像生成、视频创作、音乐生成、代码开发、办公效率等 18+ 分类，帮助用户快速找到最适合的 AI 工具。

## 技术栈

- **前端框架**：Vue 3 (Composition API)
- **构建工具**：Vite
- **样式方案**：Tailwind CSS 3
- **路由管理**：Vue Router 4

## 功能特性

- 🔍 实时全文搜索（工具名称 + 描述）
- 📂 18+ 工具分类，带子分类展开/折叠
- 🔥 首页热门工具推荐
- 🃏 工具卡片（渐变图标 + 推荐标签）
- 📱 响应式设计，支持移动端
- 🔗 友情链接：[aijiuming.com](https://aijiuming.com) · [aijiuming.cn](https://aijiuming.cn)

## 快速开始

```bash
# 安装依赖
npm install

# 启动开发服务器（本机局域网可访问）
npm run dev

# 构建生产版本
npm run build
```

## 部署到自定义域名

如果您希望部署到自定义域名 `https://www.ainav.com`：

1. 将 `vite.config.js` 中 `base` 设置为 `https://www.ainav.com/`。
2. 使用静态站点托管服务上传 `dist` 目录，或自行配置服务器绑定该域名。
3. 将域名 DNS 指向部署服务器地址，确保 `https://www.ainav.com` 能访问到静态站点。

> 注意：本地开发时 `localhost` 地址只能用于本机预览，真正的域名访问需要域名解析和部署服务器支持。

## 友情链接

- [极速工具站 aijiuming.com](https://aijiuming.com)
- [在线工具站 aijiuming.cn](https://aijiuming.cn)

## License

MIT
