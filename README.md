# 3anyat

个人博客。极简，纯静态，托管于 GitHub Pages。

## 结构

```
├── index.html        # 首页 - 文章列表
├── about.html        # 关于页面
├── css/style.css     # 全局样式
└── posts/            # 文章
    ├── hello-world.html
    ├── static-site.html
    └── typography-matters.html
```

## 本地预览

直接用浏览器打开 `index.html`，或运行：

```bash
python -m http.server 8080
```

## 发布

推送到 `main` 分支，GitHub Pages 自动部署。
