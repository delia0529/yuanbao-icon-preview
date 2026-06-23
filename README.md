# Yuanbao Icon Stroke / Corner Preview

一个干净的续作包，用于继续维护元宝图标 Stroke、Corner、Linecap 调试页。

## 快速预览

直接打开：

- `stroke-slider.html`

这是已内联 CSS、JS、SVG 的 standalone 页面，可直接用浏览器预览。

## 继续开发

```bash
npm install
npm run dev
```

默认 Vite 入口：

- `index.html`
- `src/main.js`
- `src/styles.css`

图标源文件：

- `Icon/*.svg`

## 重新生成 standalone

```bash
npm run build:standalone
```

会生成：

- `stroke-slider-standalone.html`
- `yuanbao-icon-preview-portable.html`
- `public-preview/index.html`

## 当前版本说明

- 图标库：73 个 SVG
- `AI总结` 使用 `document_summary.svg`
- 移动端和 PC 工具列表均映射到同一套可调图标系统
- Stroke / Corner / Linecap 会同步影响图标预览、移动端示意、PC 端示意

## 已清理

本包不包含：

- `node_modules`
- 历史 zip
- 历史备份目录
- 旧 `dist`
- 旧 `preview-run`
- `.DS_Store`
- 临时解压目录
