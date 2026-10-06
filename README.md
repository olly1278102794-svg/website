# 每日成果看板

一个无需后端的个人成果记录看板。所有记录只保存在每位访问者自己的浏览器里，不会上传到 GitHub。

## 发布到 GitHub Pages

1. 在 GitHub 创建一个新的公开仓库，例如 `daily-achievements`。
2. 将本文件夹内的全部文件上传到仓库根目录（`index.html`、`README.md` 和 `.gitignore`）。
3. 进入仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. 选择 `main` 分支与 `/(root)` 文件夹，点击 **Save**。
6. 稍候片刻，GitHub 会显示公开网址，通常是：
   `https://你的用户名.github.io/daily-achievements/`

## 数据与备份

- 记录只存于当前浏览器的本地存储；每位朋友会拥有自己的独立看板。
- 使用页面右上角的“导出”定期下载 JSON 备份。
- 换设备或清除浏览器数据后，可用“导入”恢复备份。

## 本地预览

直接双击 `index.html` 即可在浏览器中使用；无需安装依赖或运行服务器。
