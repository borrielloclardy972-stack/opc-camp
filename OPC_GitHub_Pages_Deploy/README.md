# OPC超级个体训练营｜GitHub Pages 上线包

这个包已经按 GitHub Pages 根目录格式整理好，解压后把里面的文件全部上传到 GitHub 仓库即可。

## 页面入口

| 路径 | 说明 |
|---|---|
| `/` 或 `/index.html` | 登录 / 注册入口，用户与管理员权限演示 |
| `/showcase.html` | 浏览器展示页 |
| `/展示浏览器.html` | 中文名浏览器展示页 |

## 本地演示卡密

```text
用户登录：OPC-VIEW-2026
管理员登录：OPC-EDIT-2026
```

## GitHub Pages 上线步骤

1. 新建 GitHub 仓库，例如 `opc-camp`。
2. 解压本包。
3. 把解压后的所有文件上传到仓库根目录。
4. 进入 `Settings → Pages`。
5. 选择 `Deploy from a branch`，Branch 选 `main`，Folder 选 `/root`。
6. 保存后等待发布完成。

发布地址通常是：

```text
https://你的GitHub用户名.github.io/opc-camp/
```

## 注意

GitHub Pages 是静态托管。当前上传、删除、注册申请是前端演示，数据保存在当前浏览器本地。真实跨电脑 / 手机同步，需要后续接 Cloudflare Worker 后端。
