# GitHub Pages 上线说明

## 方法一：网页上传

1. 打开 GitHub。
2. 新建仓库，例如 `opc-camp`。
3. 把本文件夹里的所有文件上传到仓库根目录。
4. 打开 `Settings → Pages`。
5. Source 选择 `Deploy from a branch`。
6. Branch 选择 `main`，Folder 选择 `/root`。
7. 保存后等待 GitHub Pages 完成发布。

## 方法二：命令行上传

```bash
git init
git add .
git commit -m "上线OPC展示站"
git branch -M main
git remote add origin https://github.com/你的用户名/opc-camp.git
git push -u origin main
```

然后在 GitHub 仓库 `Settings → Pages` 里启用发布。

## 重要提醒

GitHub Pages 不提供后端数据库。当前版本用于先上线展示；真实注册审核、上传删除、手机电脑实时同步，后续需要接 Cloudflare Worker。
