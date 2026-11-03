# leolmsph Demo（静态演示包）

本目录由 `frontend` 执行 `npm run build:demo` 生成，可直接用于 GitHub Pages。

## 正确访问地址

```text
https://<user>.github.io/<repo>/
```

注意末尾的 `/`，以及必须是 `github.io`（不是 github.com 仓库文件页）。

## 启用 GitHub Pages（/docs）

1. 推送含 `docs/` 的代码
2. Settings → Pages → Deploy from a branch
3. Branch: `main`，Folder: **/docs**
4. 若白屏，请用绝对 base 重新打包：

```bash
cd frontend
VITE_BASE=/你的仓库名/ npm run build:demo
```

本地预览：`cd frontend && npm run preview:demo`
