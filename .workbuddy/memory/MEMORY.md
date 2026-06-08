# 三安小筑 - 项目笔记

## 项目概况
- 个人极简博客，纯静态文件，托管于 GitHub Pages
- 零 JavaScript，零第三方依赖，零追踪脚本
- 设计理念：内容优先，排版即设计

## 网站结构
```
index.html          ← 文章列表首页
about.html          ← 关于页面
css/style.css       ← 全局样式
posts/*.html        ← 博客文章
```

## 设计决策
- 字体：系统字体栈（无外部字体加载）
- 宽度：最大 680px（60-80 字符行长）
- 颜色：暖白背景 #fafaf9，深色文字，无高亮强调色
- 无 JS：内容型网站不需要交互框架

## 添加新文章
1. 在 `posts/` 下创建 `文章名.html`
2. 在 `index.html` 的 `.post-list` 中添加条目
3. 推送到 GitHub 即可自动发布

## 本地预览
`python -m http.server 8080` 然后用浏览器打开
