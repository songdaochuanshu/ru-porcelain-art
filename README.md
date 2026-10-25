# 天青色 · 汝瓷

单文件静态页面，用一条 `index.html`（12.7 KB，CSS 全内联）做一幅关于汝窑天青釉的排版实验：墨迹纹理背景、宋体竖排、釉色渐变。

只有 Google Fonts 的 `Noto Serif SC` 是外链，其余全部自包含——双击就能看，不需要构建。

## 本地预览

```bash
# 直接打开，或起个静态服务器
python -m http.server 8080
# 或
npx serve .
```

## 部署

任意静态托管都行，仓库根目录就是产物：

```bash
npx wrangler pages deploy . --project-name ru-porcelain-art
```

## 目录

```
index.html   整个站点（HTML + CSS + 少量内联脚本）
LICENSE      MIT
```

## 变更记录

- 2026-10-25：补 MIT LICENSE 与 README。

## License

[MIT](./LICENSE)
