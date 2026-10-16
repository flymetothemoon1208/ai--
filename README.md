# AI Governance Portfolio — Flat GitHub Pages Version

这个版本已经取消所有子文件夹，所有文件都放在 GitHub 仓库根目录，适合直接通过 GitHub 网页端逐个上传。

## 最终结构

```text
index.html
styles.css
script.js
README.md
dashboard.png
workflow.png
metrics.json
```

## GitHub Pages 部署

1. 新建 GitHub 仓库。
2. 点击 Add file → Upload files。
3. 将上面 7 个文件全部上传到仓库根目录。
4. Commit changes。
5. 进入 Settings → Pages。
6. Source 选择 Deploy from a branch。
7. Branch 选择 main，Folder 选择 / (root)。
8. 保存并等待部署完成。

页面中所有图片引用均已改为根目录路径，不再依赖 assets/ 或 data/ 文件夹。
