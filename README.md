# 学前教育教研室 GitHub 分享仓库

这个目录是为 GitHub 分享准备的本地打包版本。

## 目录说明

- `docs/`: GitHub Pages 页面目录。
- `files/`: 可直接提交到 GitHub 仓库的小文件目录。
- `release-assets/`: 超过 100 MiB 的大文件目录，只用于手动上传到 GitHub Release，不要提交到普通仓库。

## 发布步骤

1. 新建一个 GitHub 仓库。
2. 上传 `docs/`、`files/`、`.gitignore`、`LARGE_FILES.md`、`bundle-summary.json`。
3. 编辑 `docs/config.js`，把 `repo` 改成 `你的用户名/仓库名`。
4. 到 GitHub 仓库设置里开启 GitHub Pages，发布源选择 `main` 分支下的 `/docs`。
5. 新建一个 Release，标签名填 `materials`。
6. 把 `release-assets/` 里的大文件逐个上传到这个 Release。

## 当前打包结果

- 仓库内文件: 1227 个
- Release 大文件: 6 个
- 仓库内文件总大小: 1.8 GB
- Release 大文件总大小: 2.0 GB
