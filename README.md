# AI生产力地图 · 企业AI化成果全景大屏

单页静态大屏（`index.html`），基准画布 1920×1080，等比自适应任何屏幕。

## 本地预览

```bash
npx --yes serve -l 4173 .
# 或直接双击 index.html
```

## 发布

本仓库根目录即站点根目录，GitHub Pages 选择 `main` 分支 `/ (root)` 即可。

访问地址：`https://<你的用户名>.github.io/ai-productivity-map/`

## 结构

```
index.html          页面本体（样式与数据内联）
assets/logo.png     左上角标识
assets/owl.png      数字员工向导
.nojekyll           关闭 Jekyll 处理，原样发布
```
