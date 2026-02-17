# GitHub Pages 发布说明（两种方式任选其一）

## 方式A：发布根目录（推荐最省事）
GitHub 仓库 → Settings → Pages：
- Source: Deploy from a branch
- Branch: main
- Folder: /(root)
保存后访问：
https://<用户名>.github.io/<仓库名>/

## 方式B：发布 /docs
GitHub 仓库 → Settings → Pages：
- Source: Deploy from a branch
- Branch: main
- Folder: /docs
保存后访问同上链接。

> 本仓库同时提供了根目录 index.html 和 docs/index.html，
> 无论你选 root 还是 /docs 都能直接打开“程序界面”，不会再变成 README 页面。
