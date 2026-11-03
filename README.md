# leolmsph Demo（静态演示包）

本目录由 `frontend` 执行 `npm run build:demo` 生成，可直接用于 GitHub Pages。

## 启用 GitHub Pages

1. 将本仓库推送到 GitHub
2. Settings → Pages → Build and deployment
3. Source 选择 **Deploy from a branch**
4. Branch 选 `main`（或你的默认分支），Folder 选 **/docs**
5. 保存后访问：`https://<user>.github.io/<repo>/`

本地预览：

```bash
cd frontend && npm run preview:demo
```
