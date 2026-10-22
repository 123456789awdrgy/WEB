# CODEX.CN · 和 Codex 一起工作

这是一个零依赖的中文静态网站，适合直接部署到 GitHub Pages。

## 本地预览

直接用浏览器打开 `index.html`，或使用任意静态文件服务器：

```bash
npx serve .
```

## 发布到 GitHub Pages

1. 在 GitHub 新建一个公开仓库，把 `index.html`、`styles.css`、`script.js` 上传到仓库根目录。
2. 打开仓库的 **Settings → Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`。
4. 保存后等待几分钟，GitHub 会提供一个免费的 `*.github.io` 网址。

页面不需要构建步骤，也不依赖后端服务。
