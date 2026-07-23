<h1 align="center">
AcadHomepage
</h1>

<div align="center">

<a href="../README.md">English</a> | <a href="./README-zh.md">中文</a>
</div>

<p align="center">一个基于 Jekyll 和 GitHub Pages 的个人学术主页项目</p>

<p align="center">
    <br>
    <img src="./screenshot.png" width="100%"/>
    <br>
</p>

## 项目简介

这个仓库是张洋的个人学术主页源码，基于 Jekyll 和 GitHub Pages 搭建，用于展示他的教育背景、研究兴趣、科研项目、知识产权成果、荣誉奖励和组织经历。这个主页以清晰、专业的方式呈现其在测绘工程与智能系统方向的学习与实践成果。

## 技术栈

- Jekyll
- GitHub Pages
- 基于 Markdown 的内容管理
- SCSS 主题样式定制
- 图片与文件资源分别存放在 images 和 files 目录

## 仓库结构

- `_pages/` - 用 Markdown 编写的主页内容
- `_layouts/` - 页面布局模板
- `_includes/` - 侧边栏、导航栏等可复用组件
- `_sass/` - 主题样式与排版设置
- `assets/` - CSS 和 JavaScript 资源
- `files/` - 可下载文件，如 CV、专利与证书等
- `images/` - 网站图片与视觉素材

## 使用方式

1. 克隆或 Fork 这个仓库。
2. 修改 `_config.yml` 中的站点配置。
3. 用 `_pages/about.md` 替换为自己的主页内容。
4. 将图片和 PDF 文件分别放入 `images/` 和 `files/` 目录。
5. 通过 GitHub Pages 发布站点。

## 本地预览

在本地运行：

```bash
bash run_server.sh
```

然后打开：

```text
http://127.0.0.1:4000
```

## 许可证

本项目采用 MIT License。