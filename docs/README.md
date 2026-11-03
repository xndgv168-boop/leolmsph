# leolmsph Demo（静态演示包）

本目录由 `frontend` 执行 `npm run build:demo` 生成，用于 GitHub Pages。

## 正确打开方式

必须用 Pages 地址（不是 github.com 仓库文件页）：

```text
https://<user>.github.io/<repo>/
```

浏览器标题应为 **leolmsph Demo**。  
若仍看到左侧英文「Project-led」挡住右侧中文图，或底部黄条「未保存展示样式」，说明打开的是旧缓存或真实后端站点，不是本 Demo。

## 上传检查清单

1. 上传整个 `docs/` 内全部文件（`index.html`、`assets/`、`.nojekyll` 等）
2. Settings → Pages → Folder 选 **/docs**
3. 强制刷新（Cmd+Shift+R）
4. URL 末尾带 `/`

## 重新打包

```bash
cd frontend
VITE_BASE=/你的仓库名/ npm run build:demo
```
